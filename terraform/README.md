terraform remote config -backend=s3 -backend-config="bucket=tfstates" -backend-config="key=demo/vpc"

test
terraform remote config -backend=s3 -backend-config="bucket=tfstates" -backend-config="key=demo/backends"
blala
terraform remote config -backend=s3 -backend-config="bucket=tfstates" -backend-config="key=demo/frontends"

Hello
