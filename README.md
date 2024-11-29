# Supabase Kubernetes

This repository contains the charts to deploy a [Supabase](https://github.com/supabase/supabase) instance inside a Kubernetes cluster using Helm 3.

For any information regarding Supabase itself you can refer to the [official documentation](https://supabase.io/docs).

## One Click to deploy a Supabase on Alibaba Cloud

[![Deploy on AlibabaCloud ACS](https://service-info-public.oss-cn-hangzhou.aliyuncs.com/computenest.svg)](https://acs.console.aliyun.com/quick-deploy?repoUrl=https://github.com/taosher/supabase-kubernetes.git&branch=main)

Clicking this button will deploy a Supabase on Alibaba Cloud ACS, which is a serverless kubernetes. 

Alibaba Cloud ACS charges only based on the specifications of running Pods. No charges are incurred when there are no Pods running.

## What's Supabase ?

Supabase is an open source Firebase alternative. We're building the features of Firebase using enterprise-grade open source tools.

## How to use ?

You can find the documentation inside the [chart directory](./charts/supabase/README.md)

# Roadmap

- [ ] Multi-node Support

## Support

This project is supported by the community and not officially supported by Supabase. Please do not create any issues on the official Supabase repositories if you face any problems using this project, but rather open an issue on this repository.

## Contributing

You can contribute to this project by forking this repository and opening a pull request.

When you're ready to publish your chart on the `main` branch, you'll have to execute `sh build.sh` to package the charts and generate the Helm manifest.

## License

[Apache 2.0 License.](./LICENSE)
