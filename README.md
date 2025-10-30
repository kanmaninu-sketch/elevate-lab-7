# elevate-lab-7
Technologies Used:
• Amazon EC2
• Elastic Load Balancer
• Auto Scaling Group
• CloudWatch Monitoring
• Apache Web Server
# Implementation Steps:
1. Launch EC2 Instances
- Installed Apache Web Server
- Hosted index.html
2. Configure Load Balancer
- Classic Load Balancer on port 80
- Health check configured
3. Configure Auto Scaling Group
- Min: 1, Desired: 2, Max: 3 Instances
- CPU Utilization > 40% triggers scaling
4. Test Scaling Behavior
- Used Apache Benchmark
- New instance launched automatically during heavy load
# Outcome:
• Load Balancer distributes incoming traffic evenly
• Auto Scaling launches/removes instances automatically
• High Availability and Cost Efficiency achieved
