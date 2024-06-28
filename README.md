# centos-repos-config
This project is a collection of configuration files for different CentOS versions tailored to various mirror sites.

## Usage

### CentOS Stream 9

#### default

```bash
curl -o /etc/yum.repos.d/centos.repo https://raw.githubusercontent.com/JeremyTsai/centos-repos-config/master/9/default/centos.repo
curl -o /etc/yum.repos.d/centos-addons.repo https://raw.githubusercontent.com/JeremyTsai/centos-repos-config/master/9/default/centos-addons.repo
```

#### tuna

```bash
curl -o /etc/yum.repos.d/centos.repo https://raw.githubusercontent.com/JeremyTsai/centos-repos-config/master/9/tuna/centos.repo
curl -o /etc/yum.repos.d/centos-addons.repo https://raw.githubusercontent.com/JeremyTsai/centos-repos-config/master/9/tuna/centos-addons.repo
```

#### aliyun

```bash
curl -o /etc/yum.repos.d/centos.repo https://raw.githubusercontent.com/JeremyTsai/centos-repos-config/master/9/aliyun/centos.repo
curl -o /etc/yum.repos.d/centos-addons.repo https://raw.githubusercontent.com/JeremyTsai/centos-repos-config/master/9/aliyun/centos-addons.repo
```
