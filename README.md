# Convert-PascalVoc-to-Yolo-format

### Xml file format

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
    <class>--- class number ---</class>
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

### txt file format 

```
<object-class> <x> <y> <width> <height>  

```
