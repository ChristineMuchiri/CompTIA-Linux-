// scp
scp ubuntu@ip-172-31-41-26:/home/ubuntu/myfile .
scp myfile ubuntu@ip-172-31-41-26:/home/ubuntu

//rsync -only copies files that have changed
rsync -rv ubuntu@ip-172-31-41-26:/home/ubuntu/* .

// netcat
nc -l 9999
nc 172.31.41.26 9999
