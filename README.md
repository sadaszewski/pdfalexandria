# pdfalexandria

PDF Alexandria (after the famous library) is a PDF annotation application written in Qt/QML. The features of PDFA are illustrated on the following mind map and screenshots. The user interface is minimalistic and works by dragging and clicking with your mouse/touch pad. In order to add a *text box*, select some text from the PDF page on the left and drag it into the annotation space on the right. To draw an *arrow*, click and drag in empty annotation space. To add an *image*, draw a selection rectangle on the PDF page (the starting and ending point must not contain text in order for the gesture to be recognized as image capture). To draw a *freehand line* or *arrow*, right click in empty annotation space and switch drawing mode to Freehand in the popup menu. Then proceed to click and drag in the annotation space. To *highlight/outline/underline* text on the PDF page - select it, right-click it and select the desired *highlight*, *outline* or *underline* color from the popup menu. Text annotations can be deleted by right-clicking them and selecting Delete from a popup menu. Other annotations can be moved and scaled using standard mouse/touch pad actions. *Arrows* can be dragged by their ends or by the middle part. Shapes can be reconfigured and/or deleted by right-clicking them and using appropriate options from the popups that will appear. Changes are saved automatically and instantenously.

```mermaid
mindmap
  root)PDF Alexandria(
    id))Text((
      id[Highlight]
      id[Outline]
      id[Underline]
    id))Shapes((
      id{{Text box}}
        id[Markdown]
      id[Arrow]
      id[Image]
      id{{Freehand}}
        id[Lines]
        id[Arrows]
    id))Styles((
      id{{Color}}
        id[Background]
        id[Text]
      id[Thickness]
      id{{Arrow heads}}
        id[Start]
        id[End]
        id[Both]
        id[None]
```
