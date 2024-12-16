# Mlflow-basic-Ops
# Using Mlflow tracking remotely

'''bash
import dagshub
dagshub.init(repo_owner='p7-source', repo_name='Mlflow-basic-Ops', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)
  '''