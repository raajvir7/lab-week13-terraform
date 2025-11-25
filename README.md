- When is the state file created?
When the terraform apply is successfully completed.

- When is the lock file present?
It is temporarily present after entering `terraform apply` and before typing `yes`.

- Is the lock file always in the bucket after it is created?
No, the lock file is only temporarily present in the bucket, until the terraform apply is applied successfully.  

![state-file](state-file.png)
![lock-file](lock-file.png)

