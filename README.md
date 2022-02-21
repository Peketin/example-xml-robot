# Robot Framework XML examples

This example robot demonstrates how to parse, query, and modify XML using Robot Framework.

Some of the things you can do include:

- Parse an XML file
- Get elements from XML by XPath
- Get elements from XML by element value
- Get elements from XML by attribute value
- Get element children from XML by XPath
- Access XML element object attributes
- Get attribute values from XML by XPath
- Get named attribute value from XML by XPath
- Save XML to a file
- Remove elements from XML by XPath
- Remove element attributes from XML by XPath
- Set XML element attribute value
- Add attribute to XML element by XPath
- Transform XML using XSLT

See the [XML library documentation](https://robocorp.com/docs/libraries/built-in/xml) for more examples and a complete list of keywords.

## The example XML file

```xml
<?xml version="1.0" encoding="UTF-8"?>
<robots>
    <robot id="MK-I">
        <price currency="USD">1000</price>
        <nick-name>Spider</nick-name>
        <components>
            <legs>8</legs>
            <eyes>20</eyes>
        </components>
        <customization-options>
            <colors>
                <color>gold</color>
                <color>silver</color>
                <color>bronze</color>
            </colors>
            <power-sources>
                <power-source type="solar"/>
                <power-source type="lithium-ion-battery"/>
                <power type="coal"/>
            </power-sources>
        </customization-options>
        <dimensions>
            <dimension type="weight" unit="kg" value="160"/>
            <dimension type="height" unit="cm" value="240"/>
            <dimension type="width" unit="cm" value="300"/>
            <dimension type="length" unit="cm" value="150"/>
        </dimensions>
    </robot>
    <robot id="MK-II">
        <price currency="USD">2000</price>
        <nick-name>Quad Arms</nick-name>
        <components>
            <arms>4</arms>
            <legs>2</legs>
        </components>
        <customization-options>
            <colors>
                <color>bronze</color>
            </colors>
            <power-sources>
                <power-source type="hamster"/>
                <power type="steam"/>
            </power-sources>
        </customization-options>
        <dimensions>
            <dimension type="weight" unit="kg" value="40"/>
            <dimension type="height" unit="cm" value="100"/>
            <dimension type="width" unit="cm" value="60"/>
            <dimension type="length" unit="cm" value="70"/>
        </dimensions>
    </robot>
    <robot id="MK-III">
        <price currency="USD">50000</price>
        <nick-name>Eye Spy With Ten Little Eyes</nick-name>
        <components>
            <eyes>10</eyes>
        </components>
        <customization-options>
            <colors>
                <color>midnight</color>
                <color>blue</color>
            </colors>
            <power-sources>
                <power-source type="solar"/>
            </power-sources>
        </customization-options>
        <dimensions>
            <dimension type="weight" unit="kg" value="5"/>
            <dimension type="height" unit="cm" value="30"/>
            <dimension type="width" unit="cm" value="40"/>
            <dimension type="length" unit="cm" value="80"/>
        </dimensions>
    </robot>
</robots>
```
