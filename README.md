# Sút Bóng TV API Tester

Dự án độc lập chỉ kiểm tra nguồn Sút Bóng TV, không liên quan tới repo sport-api chính.

## Chạy Windows
```powershell
python -m pip install -r requirements.txt
python scripts/update.py
```

Kết quả: `thethao.m3u`, `epg.xml`, `sources.json`.

## GitHub Actions
Push lên GitHub, vào tab Actions, chọn **Test Sút Bóng TV**, bấm Run workflow.
Workflow lưu các output làm artifact để tải về kiểm tra.

Config nguồn nằm trong `config.json`.
