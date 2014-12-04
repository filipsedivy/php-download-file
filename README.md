Exensions for file downloads

## What is needed
[Nete Framework](http://nette.org/)


## How to install
Moves the file to a folder anywhere you have set in RoboLoader.


## How to use

### Easy to use
```php
$downloadFile = new \FS\DownloadFile;
$downloadFile->download('data/file.exe');
```

### Advanced settings
```php
$filePath = 'data/file.exe';
$fileName = 'install.exe';
$contentType = 'application/octet-stream';
$downloadFile = new \FS\DownloadFile;
$downloadFile->speed(10); // 10 kb/s
$downloadFile->download($filePath, $fileName, $contentType);
```

