# GLB to USDZ Converter 

### **Working Solution**
-  **Functional GLB to USDZ converter** (Python)
-  **Apple AR Quick Look compatible** USDZ files
-  **Proper uncompressed ZIP format** (Apple standard)
-  **Validated and tested** on Windows


## How to run this

### **Command**
```bash
python glb_to_usdz_advanced.py input.glb output.usdz
```

### **Example Output**
```
[Info] Creating ADVANCED USDZ file...
[Info] Input: input.glb
[Info] Output: output.usdz
[Success] GLB file loaded!
[Info] Vertices: 1326
[Info] Faces: 1326
[Success] USDZ file created: output.usdz
[Info] File size: 123596 bytes
[Info] This file should work with Apple AR Quick Look and iOS AR apps
```

##  Details

### **Core Features**
- **Mesh Data Extraction**: Vertices, faces, normals, UVs
- **USD Structure**: Proper USD file format with materials
- **ZIP Archive**: Uncompressed ZIP (Apple requirement)
- **Z-up Axis**: Standard GLTF coordinate system

### **File Format Compliance**
- ✅ **Uncompressed ZIP** (Apple requirement)
- ✅ **Proper USD syntax** with materials
- ✅ **Single model.usda file** in archive
- ✅ **Z-up coordinate system** (GLTF standard)







