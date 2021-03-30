# Cloud-Benchmark
These utilities have been developed to assist you in calculating the overall size of a cloud deployment.

## Running an audit
+ Connect to Cloud Shell within the provider in question
+ Execute the following command: 
```shell
curl https://raw.githubusercontent.com/CrowdStrike/Cloud-Benchmark/main/benchmark.sh | /bin/bash
```

Results will be calculated and displayed directly to your terminal.

## Notes
- Scripts can be executed directly as shown above, or downloaded and then executed at a later time.
    + Don't forget to set execution permissions on `benchmark.sh` if you decide to download and execute later.
- Downloaded audit scripts are developed using Python 3.
- Audit scripts are removed after the process completes.
- As part of the audit, necessary dependencies are installed based upon cloud provider.

## License
These scripts are provided to the community, for free, under the Unlicense license. As such, these scripts
carry no formal support, express or implied.

## Questions?
Please submit an issue or pull request and we will address the issue as quickly as possible.