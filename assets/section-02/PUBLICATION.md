# Section two publication

Destination verified through the connected Google Drive API on 2026-09-05.

- Existing parent: [kids book](https://drive.google.com/drive/folders/181gunc7k4YIaNPoFy1uQq-AppJ63z7BT).
- Section folder: [Section 02 — Time and Primates](https://drive.google.com/drive/folders/1wm8GxfQHEoLbV9dzOAID2QFJzfQI4Rzz).
- Folder ID: `1wm8GxfQHEoLbV9dzOAID2QFJzfQI4Rzz`.
- Parent ID was confirmed by metadata readback. Folder is private; existing sharing remains unchanged.

## Publication gate

All six selected section-two spreads have been uploaded after independent visual QA and the orchestrator's own inspection. Each upload has been read back through Drive metadata or the destination folder listing, confirming PNG type and matching local byte size. Drive publication is complete; user approval of the new artwork remains a separate status. No raw family photographs, private reference files, or failed candidates were uploaded.

Browser access has resumed after the Mac lock. The section folder was verified empty before the first upload. Download, independently review, and upload only passed selections.

The `google_drive_upload_file` connector accepts `file_uri` as an absolute local file path, with `file_name`, `mime_type`, and `parent_folder_id`. This route was successfully verified with page 1. After upload, verify returned ID, MIME type, size, and parent through Drive metadata before recording publication as complete. Record the local SHA-256 for every selected uploaded file. Independent QA passes do not constitute user approval.

## Completed uploads

| Scene | Selected local path | Drive file | Bytes | Local SHA-256 | Verification |
| --- | --- | --- | --- | --- | --- |
| section-02-page-01 | `assets/section-02/page-01/spread-v01.png` | [Aiden_Section02_Page01_Back_to_the_Tree.png](https://drive.google.com/file/d/123Dib_2dxKL4mRY3k1lH1zG_g9xYBixf/view?usp=drivesdk) | 2312192 | `c3717ca941544028e86afe42272cfc4570b0cf70ee000caf98b67e060987d7e4` | Independent QA passed and parent inspected; upload and metadata readback 2026-09-05 confirmed PNG, byte size, and section parent. User approval remains separate. |
| section-02-page-02 | `assets/section-02/page-02/spread-v01.png` | [Aiden_Section02_Page02.png](https://drive.google.com/file/d/1fGzcnUkz88X238eCjkqC7grivXGYxKGF/view?usp=drivesdk) | 2488597 | `1b157e36f03b4a8005d8078ecdd0af2c6c4bcc152ac91ef168319d35b83aea7a` | QA passed; parent inspected. Upload and section-folder readback confirmed PNG and matching bytes on 2026-09-05. |
| section-02-page-03 | `assets/section-02/page-03/spread-v2.png` | [Aiden_Section02_Page03.png](https://drive.google.com/file/d/1IU0g-N_vtSislynLr_-rzJHYHH3Rhstk/view?usp=drivesdk) | 2527112 | `24ae216b6f03a9d97289afd9a581831f8ae22a2bd592d15188d84cd557e54e0a` | QA passed; parent inspected. Upload and section-folder readback confirmed PNG and matching bytes on 2026-09-05. |
| section-02-page-04 | `assets/section-02/page-04/spread-v2.png` | [Aiden_Section02_Page04.png](https://drive.google.com/file/d/1_IL19aG52IKXjy5YW5tObSIiSoD2FqxC/view?usp=drivesdk) | 2165482 | `9dd643c5209ecf6cb92188c780e7f85dd34306a6a47ee32540da1d4fd233211f` | QA passed; parent inspected. Upload and section-folder readback confirmed PNG and matching bytes on 2026-09-05. |
| section-02-page-05 | `assets/section-02/page-05/spread-v2.png` | [Aiden_Section02_Page05.png](https://drive.google.com/file/d/1360xjsmRSGvFln9YvAGkHGCc9QWIyBpk/view?usp=drivesdk) | 2583255 | `ec156e9d61f6e0dc580b652dbdd660e3cda270987a8cedc0e90e95c8dceb2b8e` | QA passed; parent inspected. Upload and section-folder readback confirmed PNG and matching bytes on 2026-09-05. |
| section-02-page-06 | `assets/section-02/page-06/spread-v2.png` | [Aiden_Section02_Page06.png](https://drive.google.com/file/d/1IoAQixmXdCAgc4cfjXeNLtnRaQOZiqCt/view?usp=drivesdk) | 2340276 | `6b7ab7c3abbae38e072f0906ea09f4ee7f73e83f3133594baefc637f84daa0aa` | QA passed; parent inspected. Upload and metadata readback confirmed PNG, matching bytes, and section parent on 2026-09-05. |

## Git binary publication

The user explicitly requested actual selected artwork in Git as well as Drive. This commit stores the six original selected PNGs at the `repository_path` entries in [manifest.json](manifest.json). Existing SHA-256 values apply to both copies. The Git tree contains the six actual binaries together with this catalog; branch publication and remote hash verification are checked by the publishing agent before reporting completion. No raw references or rejected candidates are included.
