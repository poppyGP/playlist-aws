# playlist-aws

poppyGP Playlist


Overview
--------

__AWS Infrastructure Components__

 - __S3__ - bucket to which `xspf` playlist is uploaded
 - __Lambda__ - runs code upon playlist upload to S3 bucket
 - __RDS__ - database in which playlist track information is stored by Lambda 
 - __API Gateway__ - receives `GET` requests from poppyGP client
