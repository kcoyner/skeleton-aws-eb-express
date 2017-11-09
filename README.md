# skeleton-aws-eb-express

### Basic skeleton for an AWS ElasticBeanstalk instance using Node and Express

#### Deployment steps:

1.  ```npm install```

2.  ```eb init -i```

3.  ```eb create <environment name> [options]```

Run ```eb create --help``` to see options and consider using:

	-i t1.micro   -s   -p node.js   -k <ssh keyname>
