Aside plugin for cKeditor.  Adds two buttons to the cKeditor menu for aside left and aside right.  

To install:

 - Add this folder to the cKeditor plugins folder
 - Add the following CSS to cKeditor's content.css file:


aside {
  float:left;
	width:200px;
	padding: 20px;
	background-color: #E9E2E2;
	margin: 15px 15px 15px 0;
}


 - Add the following CSS to the editor.css file of whichever theme is being used (kama is the default, so path would be skins/kama/editor.css):

.cke_icon{background-image:url(../../plugins/aside/images/aside.gif);background-position: 0;}
.cke_skin_kama a.cke_button_asideRight .cke_icon {background-image:url(../../plugins/aside/images/aside-right.gif);background-position: 0;}
