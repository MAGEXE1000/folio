# Folio

Offline Document Scanner (Android) and Vector PDF Workbench (Windows WinUI 3 + Rust).

- **Mobile**: Kotlin, Jetpack Compose Material 3 Expressive, CameraX, native Rust image/PDF core (`scanner_core`).
- **PC**: WinUI 3 (.NET 8) + native Rust PDF engine (`folio_pdf_core`) with vectorized object detection, font-matched text editing, automatic watermark removal, OCR, forms, redaction, organize/merge/split, Office conversion, PDF diff, and built-in GitHub updater.
