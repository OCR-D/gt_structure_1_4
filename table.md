<link rel="stylesheet" href="table_hide.css"/>
<div>
   <h2>Details</h2>
   <ul>
      <li>
         <a href="metadata">Metadata</a>
      </li>
      <li>
         <a href="overview">Detailed table view</a>
      </li>
   </ul>
</div>
<div class="metadata">
   <h2>Metadata</h2>
   <dl class="grid">
      <dt>Name:</dt>
      <dd>gt_structure_1_2_2</dd>
      <dt>Description:</dt>
      <dd>OCR-D Struktur-Ground Truth</dd>
      <dt>Language:</dt>
      <dd>deu</dd>
      <dt>Format:</dt>
      <dd>Page-XML</dd>
      <dt>Time:</dt>
      <dd>1600-1900</dd>
      <dt>GT Type:</dt>
      <dd>data_structure</dd>
   </dl>
   <details>
      <summary>More Information</summary>
      <dl class="more-grid">
         <dt>Transcription Guidelines:</dt>
         <dd>OCR-D-GT-Guideline, Part: Structur Ground Truth https://ocr-d.de/en/gt-guidelines/trans/structur_gt.html</dd>
         <dt>License:</dt>
         <dd>CC0 1.0</dd>
         <dt>Project:</dt>
         <dd>OCR-D</dd>
         <dt>Project-URL:</dt>
         <dd>https://ocr-d.de/</dd>
      </dl>
   </details>
   <h2>Compressed table view</h2>
   <div>
      <table class="noStyle">
         <tr>
            <td>💡 You can show and hide individual columns of the table.<br/>Click the corresponding button.
                            <details>
                  <summary>Legend</summary>
                  <dl class="grid">
                     <dt>TxtRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lytextregion.html"
                           target="_blank">TextRegion</a>
                     </dd>
                     <dt>ImgRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyBildbereiche.html"
                           target="_blank">ImageRegion</a>
                     </dd>
                     <dt>LineDrawRegion</dt>
                     <dd>LineDrawingRegion</dd>
                     <dt>GraphRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyGraphik.html"
                           target="_blank">GraphicRegion</a>
                     </dd>
                     <dt>TabRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyTabellen.html"
                           target="_blank">TableRegion</a>
                     </dd>
                     <dt>ChartRegion</dt>
                     <dd>ChartRegion</dd>
                     <dt>SepRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lySeparatoren.html"
                           target="_blank">SeperatorRegion</a>
                     </dd>
                     <dt>MathRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyMathematische_Zeichen.html"
                           target="_blank">MathsRegion</a>
                     </dd>
                     <dt>ChemRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyChemische_Symbole.html"
                           target="_blank">ChemRegion</a>
                     </dd>
                     <dt>MusicRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyNotenzeichen.html"
                           target="_blank">MusicRegion</a>
                     </dd>
                     <dt>AdRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyWerbung.html"
                           target="_blank">AdvertRegion</a>
                     </dd>
                     <dt>NoiseRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lyRauschen.html"
                           target="_blank">NoiseRegion</a>
                     </dd>
                     <dt>UnkownRegion</dt>
                     <dd>
                        <a href="https://ocr-d.de/de/gt-guidelines/trans/lySonstiges.html"
                           target="_blank">UnkownRegion</a>
                     </dd>
                     <dt>CustomRegion</dt>
                     <dd>CustomRegion</dd>
                  </dl>
               </details>
            </td>
            <td>
               <div class="grid-container">
                  <button onclick="document.getElementById('table_id').classList.toggle('hide2')">
                     <i>TxtRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide3')">
                     <i>ImgRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide4')">
                     <i>LineDrawRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide5')">
                     <i>GraphRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide6')">
                     <i>TabRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide7')">
                     <i>ChartRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide8')">
                     <i>SepRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide9')">
                     <i>MathRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide10')">
                     <i>ChemRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide11')">
                     <i>MusicRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide12')">
                     <i>AdRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide13')">
                     <i>NoiseRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide14')">
                     <i>UnkownRegion</i>
                  </button>
                  <button onclick="document.getElementById('table_id').classList.toggle('hide15')">
                     <i>CustomRegion</i>
                  </button>
               </div>
            </td>
         </tr>
      </table>
      <table id="table_id" class="display">
         <thead>
            <tr>
               <th>document</th>
               <th>TxtRegion</th>
               <th>ImgRegion</th>
               <th>LineDrawRegion</th>
               <th>GraphRegion</th>
               <th>TabRegion</th>
               <th>ChartRegion</th>
               <th>SepRegion</th>
               <th>MathRegion</th>
               <th>ChemRegion</th>
               <th>MusicRegion</th>
               <th>AdRegion</th>
               <th>NoiseRegion</th>
               <th>UnkownRegion</th>
               <th>CustomRegion</th>
               <th>TextLine</th>
               <th>Page</th>
            </tr>
         </thead>
         <tbody/>
      </table>
   </div>
</div>
