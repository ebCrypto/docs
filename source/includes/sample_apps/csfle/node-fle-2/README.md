These are the source files to build Node sample
applications to use Queryable Encryption following
KMS providers:

- AWS
- GCP
- Azure
- Local KMS

To build the Node applications, run the following command from the parent of this directory:

    python build.py --project node-fle-2

To test your built applications, run the following
command from the parent of this directory:

    python -m unittest test.TestNodeFLE2
