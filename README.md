# alitomate-API

## Add Report :
- **Endpoint :** ```/report```
- **Method : POST**
- Body :  
```
{
  "nama" : "",
  "nomor_telepon" : "",
  "detail_lokasi" : "",
  "keterangan_kebakaran" : "",
  "location" : ""
  
}
```
- Response : 
```
{
  "userreport": {
  "nama" : "",
  "nomor_telepon" : "",
  "detail_lokasi" : "",
  "keterangan_kebakaran" : "",
  "location" : ""
  }
}
```

## Upload Image
- **Endpoint :** ```/upload```
- **Method : POST**
- Body :
```
{
  "file" : ""
}
```
- Response : 
```
{
  "message": "",
    "url":
}
```

