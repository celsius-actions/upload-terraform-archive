## Usage

Add the following step to your workflow:

```yaml
- id: upload-files
  uses: celsius-actions/upload-terraform-archive
  with:
    content-directory: <PATH_TO_TF_FILES>
    upload-url: <UPLOAD_URL>
```
