


# popUp-menu
This project provides a js 'engine' to manage a one layer popUp menu

one important feature 


<img src="PopUp-menu.png" alt="drawing" style="display: block; margin-left: auto; margin-right: auto;width:400px;" class="center"/>
<!-- ![GitHub](/PopUp-menu.png =10x) -->
<!-- # Format: ![Alt Text](url) -->


Developers, in general and web developers in particular, tend not to make use of popUps.<br>
They should! Especially when developing intranet or desktop applications.<br>
The below image shows the popUp of the 'GitHub desktop' application, which believe or not is an HTML page (as shown by the right panel: 'Developer tools').

<img src="gitHub-desktop.F12.png" alt="drawing" style="display: block; margin-left: auto; margin-right: auto;width:400px;" class="center"/>
<!-- ![GitHub](/gitHub-desktop.F12.png) -->

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
