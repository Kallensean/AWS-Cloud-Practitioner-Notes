EC2:
	 **Instance Types:**
	 - *General purpose* - ==balance== of compute memory and networking resources
	 - *Compute optimized* - Ideal for compute-bound apps that benefit from ==high-performance processors== 
	 - *Memory optimized* - deliver fast performance for workloads that process large datasets in memory. 
	 - *Accelerated computing* - use hardware accelerators, or coprocessors, to perform some ==functions more efficiently== than is possible in software running on CPU's.
	 - *Storage optimized* - designed for workloads that require high, sequential read and write access to large ==datasets== on local storage.
	**Pricing:**
	 - *On-demand* - ideal for short term, irregular workload that cannot be interrupted. No upfront costs or min. contracts apply. Instances run continuously
	 - *Reserved Instances* - Billing a discount applied to the use of On-Demand Instances in your account
		 - *Standard Reserved Instance* - Good fit if you know the EC2 instance type and size needed for the steady-state apps and which AWS region you plan to run them. They need ==Instance type and size, OS and Tenancy==
		 - *Convertible Reserved Instance* - If you need to run your EC2 instances in different Availability Zones or different instance types
	 - *EC2 Instance Savings Plans* - Reduces the EC2 instance costs when you make an hourly spend commitment to an instance family and Region for 1 or 3 year term. Up to 72% compared to On-demand rates.
	 - *Spot Instances* - Ideal for workloads with flexible start and end times, or that withstand interruptions. Can be up to 90% off On-Demand prices. 


Elastic Load Balancing(ELB):
	Regional construct - runs at regional level
	Automatically scalable - no change to cost
	Decoupled architecture - front end doesn't know about back end 