steps:
```
terraform init
terraform apply
terraform output foo
```

expected:
```
foo
bar
```

actual:
```
foo = <<EOT
foo
bar

EOT
```
