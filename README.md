# awx

create a VPC to connect our EC2 instances placed in different AZs and give them internet connection. From this scenario:

VPC in a region (me: ap-southeast-3);
Subnet on each AZ (3 in total);
Internet gateway;
Route table;
Security group.

https://res.cloudinary.com/practicaldev/image/fetch/s--7VUDzLJ8--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_800/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/vapibl8s6lhlzwd5p2ib.png

vpc.yml