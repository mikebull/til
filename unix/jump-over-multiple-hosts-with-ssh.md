# Jump over multiple hosts with SSH

If you're in a position where you need to SSH into a private host, where your machine does not have access, but a machine you can access does, an alternative to tunneling is to use jump hosts.

To do this, use:

```bash
$ ssh -J deploy@ec2-00-00-00-00.eu-west-2.compute.amazonaws.com deploy@123.123.123.123
```

This will grant you access to 123.123.123.123 via the publicly-accessible ec2 instance.