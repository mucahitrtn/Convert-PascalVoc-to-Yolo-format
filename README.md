# Convert-PascalVoc-to-Yolo-format

### Pascal voc annotation

```
<annotation>
  <folder>-------</folder>
  <file>--- File name ---</file>
  <path>--- Path ---/</path>
  <source>
    <database>Unknown</database>
  </source>
  <size>
    <width>1440</width>
    <height>1080</height>
    <depth>3</depth>
  </size>
  <object>
    <name>--- class name ---</name>
    <class>--- object-class ---</class>
    <pose>0</pose>
    <bndbox>
      <xmin>--- xmin ---</xmin>
      <ymin>--- ymin ---</ymin>
      <xmax>--- xmax ---</xmax>
      <ymax>--- ymax ---</ymax>
    </bndbox>
  </object>
</annotation>
```

### Yolo annotation 

```
<object-class> <x> <y> <width> <height>  
```
