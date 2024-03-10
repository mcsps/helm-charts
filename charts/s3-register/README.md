# s3-register

Helm Chart to create a user and a bucket on a S3 backend, i.e. [Minio](https://github.com/eumel8/minio/tree/fix/securitycontext)

required  values:

```yaml
# vcluster clustername, this will be the name of the bucket and the created user
clustername: vc
# S3 registration server url
s3:
  url: http://minio.minio:9000
```

S3 secretKey will be auto-generated and stored in a Secret. As part of [Vcluster Backup](https://github.com/eumel8/vcluster-backup) you can use this Secret as reference to perform periodically backups of a Vcluster.

hint: remove of the chart will remove the S3 bucket with all data without any questions

