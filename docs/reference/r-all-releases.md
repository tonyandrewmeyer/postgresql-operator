# Release Notes
Here you will find release notes for major revisions of this charm that are available in the [Charmhub `stable` channel](https://juju.is/docs/juju/channel#heading--risk).

To see  **all** charm revisions, check the [Charmed PostgreSQL Releases page](https://github.com/canonical/postgresql-operator/releases) on GitHub.

## At a glance

The table below is a high-level overview of the architectures and integrations that are supported by each charm revision. 

| Revision | PostgreSQL | amd64 | arm64 | [TLS  encryption](/t/9685)* | [Monitoring (COS, Grafana)](/t/10600)  | [Tracing (Tempo K8s)](/t/14521)  |
|:--------:|:-----:|:-----:|:-----:|:--------------------:|:---------------:|:--------------------:|
|     [468](/t/15378)  | 14.12 |   :white_check_mark:    |:heavy_multiplication_x: |          :white_check_mark:           |        :white_check_mark:         |         :white_check_mark:           |
|      [467](/t/15378) | 14.12 |  :heavy_multiplication_x:  |   :white_check_mark:   |          :white_check_mark:            |        :white_check_mark:         |         :white_check_mark:           |
|     [430](/t/14067)  | 14.11 |   :heavy_multiplication_x:   |:white_check_mark: |          :white_check_mark:           |        :white_check_mark:         |         :white_check_mark:           |
|      [429](/t/14067) | 14.11 |  :white_check_mark:   |    :heavy_multiplication_x:   |          :white_check_mark:            |        :white_check_mark:         |         :white_check_mark:           |
|      [363](/t/13124) | 14.10 |  :white_check_mark:   |    :heavy_multiplication_x:   |          :white_check_mark:            |        :white_check_mark:        |           :heavy_multiplication_x:         |
|      [351](/t/12823) | 14.9 |  :white_check_mark:    |    :heavy_multiplication_x:   |            :heavy_multiplication_x:          |        :white_check_mark:         |           :heavy_multiplication_x:         |
|      [336](/t/11877) | 14.9 | :white_check_mark:    |    :heavy_multiplication_x:   |            :heavy_multiplication_x:          |       :white_check_mark:          |           :heavy_multiplication_x:        |
|      [288](/t/11876) | 14.7 | :white_check_mark:    |    :heavy_multiplication_x:   |           :heavy_multiplication_x:          |       :heavy_multiplication_x:     |       :heavy_multiplication_x:     |


**TLS encryption***: Support for **`v2` or higher** of the [`tls-certificates` interface](https://charmhub.io/tls-certificates-interface/libraries/tls_certificates). This means that you can integrate with [modern TLS charms](https://charmhub.io/topics/security-with-x-509-certificates).

For more details about a particular revision, refer to its dedicated Release Notes page.
For more details about each feature/interface, refer to their dedicated How-To guide.

### Plugins/extensions

For a list of all plugins supported for each revision, see the reference page [Plugins/extensions](/t/10946).