# Client-side encrypted backups of Kubernetes PVCs to S3-compatible storage

This repo contains example files for backing up Kubernetes PVCs using a CronJob to S3-compatible storage, with a tool called restic and client-side encryption. Examples are given for AWS S3 and Backblaze B2, but they could be adapted to other backends described in the [restic docs](https://restic.readthedocs.io/en/latest/030_preparing_a_new_repo.html).

Please see my blog posts for more information and step-by-step instructions: 

* [AWS S3](https://alexlubbock.com/encrypted-backup-kubernetes-pvc-aws-s3)
* [Backblaze B2](https://alexlubbock.com/encrypted-backup-kubernetes-pvc-backblaze-b2)