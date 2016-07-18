2016 - 07 -18
I begin writing ileaned-today
- Google clound storage
    To change meta-data file on google clound storage.You have to do:
      1. Config account at local: gcloud auth login
      1. Set your account permission owner for bucket
      2. gsutil setmeta -h 'content-type:image/jpeg' gs://your-bucket/*.jpg
