workspace(name = "tf_ingest")

local_repository(
  name = "org_tensorflow",
  path = __workspace_dir__ + "/tensorflow",
)

load('//tensorflow/tensorflow:workspace.bzl', 'tf_workspace')
tf_workspace("tensorflow/", "@org_tensorflow")
