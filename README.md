Custom Views - Custom Fan Controller
============================================================================

Solution code for Advanced Android with Kotlin Codelab 

Introduction
------------

Custom Fan Controller is an app for making custom DialView.

- In this codelab, the Fan DialView starts with off. 
- When you click on DialView, the indicator moves to 1.
- Another click, moves to 2.
- Another click, moves to 3.
- Another one, moves to off again.

## Summary
* Subclass an existing view and override methods.
* Create a subclass of [View](https://developer.android.com/reference/android/view/View) to customize everything.
* Override View methods such as [onDraw()](https://developer.android.com/reference/android/view/View.html#onDraw%28android.graphics.Canvas%29)
* Use [invalidate()](https://developer.android.com/reference/android/view/View.html#invalidate()) to force a draw or redraw of the view.
* Allocate space and initialize variables outside onDraw().
* Override [performClick()](https://developer.android.com/reference/android/view/View.html#performClick())
* Use XML layout file.
* Create attrs.xml file to define custom attributes.

### Screenshots

<table>
  <tr>
    <td>
      <img src = "https://user-images.githubusercontent.com/29761752/234155352-07a5f90d-0020-4e99-83e7-e4318bd2dfc8.png"/>
    </td>
    <td>
      <img src = "https://user-images.githubusercontent.com/29761752/234155358-ce100fc7-d3b5-4c97-a131-a129a85f01d5.png"/>
    </td>
    <td>
      <img src = "https://user-images.githubusercontent.com/29761752/234155363-e1d036f3-8c7b-4175-9939-9f8ec6ebe4d9.png"/>
    </td>
  </tr>
  <tr>
    <td>
      <img src = "https://user-images.githubusercontent.com/29761752/234155373-734ba694-7251-45e9-b67b-1067d3742808.png"/>
    </td>
  </tr>
</table>
