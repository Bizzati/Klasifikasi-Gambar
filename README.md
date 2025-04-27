# Running requirements

## Environment setup

```bash
pip install -r requirements.txt
```

##  Model Formats

- **SavedModel**: Folder standar TensorFlow yang menyimpan graph dan bobot model lengkap.
- **TF-Lite**: File `.tflite` ter‐optimasi untuk inference di perangkat mobile atau embedded (Android, iOS, Raspberry Pi).
- **TFJS**: File `model.json` + `*.bin` untuk menjalankan model langsung di browser atau Node.js.
