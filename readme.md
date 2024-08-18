# readme file
import dagshub
dagshub.init(repo_owner='sachin62025', repo_name='MLFlow', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)
MLFLOW_PASSWORD_URI : 65d50977c1a608302e1a618f66636dff1acebd85