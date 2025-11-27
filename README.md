# my_vulnerabilities

## 1. Cloud Native Projects
### 1.1 bitnami/laravel
#### 1.1.1 [DONE] CVE-2021-21979: APP_KEY is fixed in docker image bitnami/laravel

Timeline:
* 2021-02-23 Reported to bitnami
* 2021-02-24 Fixed
* 2021-02-24 CVE number assigned
* DONE

### 1.2 meshery
#### 1.2.1 [DONE] CVE-2021-31856: A Sql Injection in Meshery
https://github.com/ssst0n3/CVE-2021-31856

Timeline:
* 2021-04-20 Discovered
* 2021-04-21 Reported to Meshery
* 2021-04-25 Fixed
* 2021-04-28 Public
* DONE

###  1.3 docker
#### 1.3.1 [DONE] CVE-2021-41089: `docker cp` allows unexpected chmod of host files

https://github.com/moby/moby/security/advisories/GHSA-v994-f8vw-g7j4

Timeline:
* 2021-04-30 Discovered
* 2021-09-24 CVE number assigned
* 2021-10-05 Public
* DONE

#### 1.3.2 [REPORTED] *** 

Timeline:
* 2021-08-24 Discovered
* 2021-08-24 Reported to docker
* 2021-08-25 Confirmed
* TODO

### 1.4 containerd

### 1.5 runc
#### 1.5.1 [Rejected] host infomation disclosure

Timeline:
* 2022-08-04 Discovered
* Rejected By Akihiro Suda: I don't think this is a vuln. Containers have been leaking loadavg, memory usage, disk usage, and other resource counters too.

#### 1.5.2 [PUBLISHED] CVE-2023-28642: AppArmor/SELinux bypass with symlinked /proc

https://github.com/opencontainers/runc/security/advisories/GHSA-g2j6-57v7-gm8c

Timeline:
* 2022-07-29 Discovered
* 2023-03-28 Reported to runc
* 2023-03-29 CVE-2023-28642 assigned
* 2023-03-29 Fixed version v1.1.5 released and cve published
* DONE

#### 1.5.3 [Rejected] runc escape with a capability

Timeline:
* 2022-06-17 Discovered
* Rejected By Cyphar: Most capabilities are unsafe to give to a non-userns container. 
