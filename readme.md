# MuleSoft training: DevFundamentals w/Mule-4

The contents in these folders contain solution files for walkthroughs covered each day.

What do these file types mean?

- .jar: most probably a MuleSoft app bundled as a .jar file

- .zip: most probably a RAML specification along with other associated RAML fragments

- .json or .xml: files used as sample data to build input/output schemas for DataWeave

<BR>
<BR>

## How to import the RAML solution into Anypoint Design Center?

- Download the zip file that represents the RAML specification (no need to unzip it)

- Log into **Anypoit Platform**: https://anypoint.mulesoft.com

- Access **Design Center**.  Click **Create > Specification**

- Provide the name: **American Flights API** (note: if you aready have one by this name, remove/rename that first)

- Once the **API Designer** opens, clikc on **three-dots** at the top-left and select **Import**

- Click on **Choose File** and point to the zip file you downloaded

- Click **Import**, and select **Yes** if prompted to overwrite the existing .raml file