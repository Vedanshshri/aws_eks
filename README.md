# aws_eks

[
  {
    "Id": "m1",
    "MetricStat": {
      "Metric": {
        "Namespace": "AWS/EC2",
        "MetricName": "CPUUtilization",
        "Dimensions": [
          {
            "Name": "InstanceId",
            "Value": "INSTANCE_ID"
          }
        ]
      },
      "Period": 300,
      "Stat": "Average"
    },
    "ReturnData": true
  }
]
