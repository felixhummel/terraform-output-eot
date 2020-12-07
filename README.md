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
<<EOT
foo
bar

EOT
```
