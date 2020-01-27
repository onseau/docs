---
tap: "google-sheets"
version: "0.x"
key: ""
name: "sheet_metadata"
doc-link: ""
singer-schema: "https://github.com/singer-io/tap-google-sheets/blob/master/tap_google_sheets/schemas/sheet_metadata.json"
description: ""
replication-method: ""
api-method:
    name: ""
    doc-link: ""
attributes:
  - name: "columns"
    type: "null"
    description: ""
  - name: "gridProperties"
    type: "object"
    description: ""
    subattributes:
      - name: "columnCount"
        type: "integer"
        description: ""
      - name: "frozenColumnCount"
        type: "integer"
        description: ""
      - name: "frozenRowCount"
        type: "integer"
        description: ""
      - name: "rowCount"
        type: "integer"
        description: ""
  - name: "index"
    type: "integer"
    description: ""
  - name: "sheetId"
    type: "integer"
    description: ""
  - name: "sheetType"
    type: "string"
    description: ""
  - name: "sheetUrl"
    type: "string"
    description: ""
  - name: "spreadsheetId"
    type: "string"
    description: ""
  - name: "title"
    type: "string"
    description: ""
---