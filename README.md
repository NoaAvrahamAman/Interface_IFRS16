# Interface_IFRS16

Finance interface from Silvernet to Chemipal.

This interface supports two types of files:

* IFRS16
* IFRS16_A

---

## Components

### DataFlow

* **CM_FIN_IN_IFRS16.xml**
  ION DataFlow – reads file from a folder and sends it to MEC.

### File Template

* **IFRS16_File.xml**
  File template definition.

### Data Objects

* **IFRS16_File.zip**
  Original data object.

* **IFRS16_Transformed.zip**
  Data object after transformation.

### Script

* **IFRS16_AddCONO.json**
  Script that:

  * Adds CONO value from file path into content
  * Converts encoding from Windows-1255 to UTF-8

### Mapper Files

* **CM_FIN_IN_IFRS16.zip**
  Files for Eclipse Mapper.
  ⚠️ Extract this ZIP before using it in Eclipse.

---

## Notes

* Make sure encoding conversion is applied before processing.
* Verify file structure matches the template before sending to MEC.
* Ensure correct file type (IFRS16 / IFRS16_A) is used during processing.






