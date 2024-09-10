# 2023-25.ML.UFS14
ciao

aws sagemaker stop-notebook-instance --notebook-instance-name "MyNotebook"

aws sagemaker create-notebook-instance \
--notebook-instance-name notebook-created-by-cli \
--lifecycle-config-name ml-pipeline-c133245a3374983l7536149t1w443234888680 \
--instance-type ml.t3.medium \
--role-arn arn:aws:iam::443234888680:role/c133245a3374983l7536149t1w44-SageMakerExecutionRole-QJe7LqWlUfAV