# Terraform Beginner Bootcamp 2023

### Refactoring the terraform task execution in GitPod
 
 The terraform CLI have changed so it would have been too chaotic and more complex to read if multi-line commands were used instead of a script

 [Install Terraform CLI](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)

 ### We can use Env Vars

 ####  env commands

 - We can list out all env variables using `env` command
 
 - We can filter specific env var using grep eg. `env | grep AWS_XXX`

 #### Setting and Unestting Env Vars

 - In the terminal we can set using 'export $Hello = 'World'```

 - In the terminal we can unset using 'unset $Hello```

 > We can set an env var temporarily when just running a command:
 
 ```sh
 Hello = 'World' ./bin/print_message
```

gp env PROJECT_ROOT='/workspace/terraform-beginner-bootcamp-2023' PROJECT_ROOT=/workspace/terraform-beginner-bootcamp-2023