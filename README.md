# tf2tfjson

Trying to convert the suffix of the file from `tf` to `tf.json`

Based on [Issue: HCL2 <-> JSON Transformer? #294](https://github.com/hashicorp/hcl/issues/294). 
I considered that it is impossible to convert HCL to JSON and back, because it depends on the application's configuration schema.

However, I think it is possible to convert `*.tf` to `*.tf.json`. So, I am trying to work on it and solve the problem.
