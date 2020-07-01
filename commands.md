# List commands

<table>
<tr><th>Command</th><th>Status</th><th>Description</th></tr>
<tr><td>EOT</td><td>[-]</td><td>Transmit status</td></tr>
<tr><td>HT</td><td></td><td>Horizontal tab</td></tr>
<tr><td>FF</td><td>[-]</td><td>Form feed</td></tr>
<tr><td>LF</td><td></td><td>Line feed - flush line image buffer</td></tr>
<tr><td>CR</td><td>[*]</td><td>Carriage return. <b>I don't flush buffer</b></td></tr>
<tr><td>DLE EOT</td><td>[-]</td><td>Transmit real-time status</td></tr>
<tr><td>DLE ENQ</td><td>[-]</td><td>Send real-time request to printer</td></tr>
<tr><td>DLE DC4</td><td>[-]</td><td>Realtime function</td></tr>
<tr><td>CAN</td><td>[-]</td><td>Cancel the print data in page mode</td></tr>
<tr><td>ESC FF</td><td>[-]</td><td>Print data in Page mode</td></tr>
<tr><td>ESC S0</td><td></td><td>Select double width [POS58]</td></tr>
<tr><td>ESC DC4</td><td></td><td>Disable double width [POS58]</td></tr>
<tr><td>ESC SP</td><td></td><td>Set right-side character spacing</td></tr>
<tr><td>ESC !</td><td>[*]</td><td>Select print mode(s). Italic not emulated</td></tr>
<tr><td>ESC $</td><td></td><td>Set absolute print position</td></tr>
<tr><td>ESC %</td><td>[-]</td><td>Select/cancel UDF charset</td></tr>
<tr><td>ESC &</td><td>[-]</td><td>Define UDF charset</td></tr>
<tr><td>ESC ( A</td><td>[-]</td><td>Control beeper tones</td></tr>
<tr><td>ESC ( Y</td><td>[-]</td><td>Specify batch print</td></tr>
<tr><td>ESC *</td><td></td><td>Select bit-image mode</td></tr>
<tr><td>ESC -</td><td>[*]</td><td>double underline not emulated</td></tr>
<tr><td>ESC 2</td><td>[*]</td><td>Select default line spacing</td></tr>
<tr><td>ESC 3</td><td>[*]</td><td>Set line spacing. Values​less than the default are not emulated.</td></tr>
<tr><td>ESC &lt;</td><td></td><td>Return home</td></tr>
<tr><td>ESC =</td><td>[-]</td><td>Select peripheral device</td></tr>
<tr><td>ESC ?</td><td>[-]</td><td>Cancel user-defined characters</td></tr>
<tr><td>ESC @</td><td></td><td>Initialize printer</td></tr>
<tr><td>ESC D</td><td></td><td>Set horizontal tab positions</td></tr>
<tr><td>ESC E</td><td></td><td>Turn emphasized mode on/off</td></tr>
<tr><td>ESC G</td><td></td><td>Turn double-strike mode on/off</td></tr>
<tr><td>ESC I</td><td></td><td>Print and feed paper</td></tr>
<tr><td>ESC J</td><td></td><td>Print and feed paper</td></tr>
<tr><td>ESC K</td><td>[-]</td><td>Print and reverse feed</td></tr>
<tr><td>ESC L</td><td>[-]</td><td>Select Page mode</td></tr>
<tr><td>ESC M</td><td>[*]</td><td>Select character font. Font C and MSR not support.</td></tr>
<tr><td>ESC R</td><td>[-]</td><td>	Select an international character set</td></tr>
<tr><td>ESC S</td><td></td><td>Select Standard mode<br/><b>The emulator only supports standard mode.</b></td></tr>
<tr><td>ESC T</td><td>[-]</td><td>Select print direction in Page mode</td></tr>
<tr><td>ESC U</td><td>[*]</td><td>Turn unidirectional print mode on/off. <i>It makes no sense for devices without mechanically moving parts.</i></td></tr>
<tr><td>ESC V</td><td>[-]</td><td>Turn 90° clockwise rotation mode on/off</td></tr>
<tr><td>ESC W</td><td>[-]</td><td>Set print area in Page mode</td></tr>
<tr><td>ESC \</td><td>[-]</td><td>Set relative print position</td></tr>
<tr><td>ESC a</td><td></td><td>Select justification</td></tr>
<tr><td>ESC c 3</td><td>[*]</td><td>Select paper sensor(s) to output paper-end signals</td></tr>
<tr><td>ESC c 4</td><td>[*]</td><td>Select paper sensor(s) to stop printing</td></tr>
<tr><td>ESC c 5</td><td>[*]</td><td>Enable/disable panel buttons</td></tr>
<tr><td>ESC d</td><td></td><td>Print and feed n lines</td></tr>
<tr><td>ESC e</td><td>[-]</td><td>Feed reverse</td></tr>
<tr><td>ESC i</td><td></td><td>Partial cut (one point left uncut)</td></tr>
<tr><td>ESC m</td><td></td><td>Partial cut (three points left uncut)</td></tr>
<tr><td>ESC p</td><td>[-]</td><td>Generate pulse</td></tr>
<tr><td>ESC r</td><td>[-]</td><td>Select print color</td></tr>
<tr><td>ESC t</td><td></td><td>Select character code table. <b>See capability profile</b></td></tr>
<tr><td>ESC u</td><td>[-]</td><td>Transmit peripheral device status</td></tr>
<tr><td>ESC v</td><td>[-]</td><td>Transmit paper sensor status</td></tr>
<tr><td>ESC {</td><td></td><td>Turn upside-down print mode on/off</td></tr>
<tr><td>FS !</td><td>[-]</td><td>	Select print mode(s) for Kanji characters</td></tr>
<tr><td>FS &</td><td>[-]</td><td>	Select Kanji character mode</td></tr>
<tr><td>FS ( A</td><td>[-]</td><td>	Select Kanji character style(s)</td></tr>
<tr><td>FS ( C</td><td>[-]</td><td>	Select code conversion method</td></tr>
<tr><td>FS ( E</td><td>[-]</td><td>	Group of commands for receipt enhancement control</td></tr>
<tr><td>FS ( L</td><td>[-]</td><td>	Select label and black mark control function(s)</td></tr>
<tr><td>FS ( e</td><td>[-]</td><td>	Enable/disable Automatic Status Back (ASB) for optional functions (extended status)</td></tr>
<tr><td>FS - </td><td>[-]</td><td>	Turn underline mode on/off for Kanji characters</td></tr>
<tr><td>FS . </td><td>[-]</td><td>	Cancel Kanji character mode</td></tr>
<tr><td>FS 2</td><td>[-]</td><td>	Define user-defined Kanji characters</td></tr>
<tr><td>FS ?</td><td>[-]</td><td>	Cancel user-defined Kanji characters</td></tr>
<tr><td>FS C</td><td>[-]</td><td>	Select Kanji character code system</td></tr>
<tr><td>FS S</td><td>[-]</td><td>	Set Kanji character spacing</td></tr>
<tr><td>FS W</td><td>[-]</td><td>	Turn quadruple-size mode on/off for Kanji characters</td></tr>
<tr><td>FS g</td><td>[-]</td><td> 	NV ram	</td></tr>
<tr><td>FS p</td><td>[-]</td><td> 	Print NV bit image	</td></tr>
<tr><td>FS q</td><td>[-]</td><td> 	Define NV bit image	</td></tr>
<tr><td>GS !</td><td></td><td>	Select character size</td></tr>
<tr><td>GS $</td><td>[-]</td><td>	Set absolute vertical print position in Page mode</td></tr>
<tr><td>GS ( A</td><td>[-]</td><td>	Execute test print</td></tr>
<tr><td>GS ( C</td><td>[-]</td><td>	Edit NV user memory</td></tr>
<tr><td>GS ( D</td><td>[-]</td><td>	Enable/disable real-time command</td></tr>
<tr><td>GS ( E</td><td>[-]</td><td>	Set user setup commands</td></tr>
<tr><td>GS ( H</td><td>[-]</td><td>	Request transmission of response or status</td></tr>
<tr><td>GS ( K</td><td>[-]</td><td>	Select print control method(s)</td></tr>
<tr><td>GS ( L / GS 8 L </td><td>[*]</td><td>Set graphics data (fn 48,49,51,52,64,65,66,67,68,69,80-85 not supported)</td></tr>
<tr><td>GS ( M</td><td>[-]</td><td>	Customize printer control value(s)</td></tr>
<tr><td>GS ( N</td><td>[-]</td><td>	Select character effects</td></tr>
<tr><td>GS ( P</td><td>[-]</td><td>	Page mode control</td></tr>
<tr><td>GS ( Q</td><td>[-]</td><td>	Commands for drawing graphics</td></tr>
<tr><td>GS ( k</td><td>[*]</td><td><b>Emulated only QRCode model 2</b></td></tr>
<tr><td>GS * </td><td>[-]</td><td>	Define downloaded bit image</td></tr>
<tr><td>GS / </td><td>[-]</td><td>	Print downloaded bit image</td></tr>
<tr><td>GS :</td><td>[-!-]</td><td>	Start/end macro definition</td></tr>
<tr><td>GS B</td><td></td><td>	Turn white/black reverse print mode on/off	Character</td></tr>
<tr><td>GS C</td><td>[-]</td><td> 	counter</td></tr> 
<tr><td>GS D</td><td>[-]</td><td>	Specify Windows BMP graphics data</td></tr>
<tr><td>GS H</td><td></td><td>	Select print position of HRI characters</td></tr>
<tr><td>GS I</td><td>[-]</td><td>	Transmit printer ID</td></tr>
<tr><td>GS L</td><td></td><td>	Set left margin</td></tr>
<tr><td>GS P</td><td>[-]</td><td>	Set horizontal and vertical motion units</td></tr>
<tr><td>GS Q 0 </td><td>[-]</td><td>	Print variable vertical size bit image</td></tr>
<tr><td>GS T</td><td>[-]</td><td>	Set print position to the beginning of print line</td></tr>
<tr><td>GS V</td><td>[*]</td><td>	Select cut mode and cut paper. <b>Cut mode C&D not emulated</b> </td></tr>
<tr><td>GS W</td><td></td><td>	Set print area width</td></tr>
<tr><td>GS \</td><td>[-]</td><td>	Set relative vertical print position in Page mode</td></tr>
<tr><td>GS ^</td><td>[-]</td><td>	Execute macro</td></tr>
<tr><td>GS a</td><td>[-]</td><td>	Enable/disable Automatic Status Back (ASB)</td></tr>
<tr><td>GS b</td><td>[-]</td><td>	Turn smoothing mode on/off</td></tr>
<tr><td>GS c </td><td>[-]</td><td>	Print counter</td></tr>
<tr><td>GS f</td><td></td><td>	Select font for HRI characters</td></tr>
<tr><td>GS g 0</td><td>[-]</td><td>	Initialize maintenance counter</td></tr>
<tr><td>GS g 2</td><td>[-]</td><td>	Transmit maintenance counter</td></tr>
<tr><td>GS h</td><td></td><td>	Set barcode height</td></tr>
<tr><td>GS j</td><td>[-]</td><td>	Enable/disable Automatic Status Back (ASB) for ink</td></tr>
<tr><td>GS k</td><td></td><td>	Print barcode</td></tr>
<tr><td>GS r</td><td>[-]</td><td>	Transmit status	Status</td></tr>
<tr><td>GS v 0 </td><td></td><td>	Print raster bit image</td></tr>
<tr><td>GS w</td><td></td><td>	Set barcode width</td></tr>
<tr><td>GS z 0</td><td>[-]</td><td>	Set online recovery wait time</td></tr>

</table>







