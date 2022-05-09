# Keptn Integrations

Keptn as a control-plane integrates with various different tools and can be extended with your own tools.
This can be achieved through specialized integration services or through generic services.

This repository lists Keptn Integrations and ideas for new ones.

## References

- [Keptn Integrations Documentation](https://keptn.sh/docs/integrations/) - 
  Lists integrations available for Keptn.
  You can also find them on [ArtifactHub](https://artifacthub.io/packages/search?kind=10&sort=relevance&page=1).
- [Keptn Webhook Service](https://keptn.sh/docs/0.14.x/integrations/webhooks/) -
  Keptn has a built-in capability to call external HTTP endpoints as part of sequence task orchestration.
  This can be used to simplify the integration of various third-party tools such as testing services, CI/CD pipelines, and incident management service.
- [Keptn Job Executor Service](https://github.com/keptn-contrib/job-executor-service) -
  Allows running customizable tasks with Keptn as Kubernetes Jobs.
- [Pending feature requests for new integrations](https://github.com/keptn/integrations/issues)

## Developer information

- [Hosting new integrations](https://github.com/keptn-sandbox/contributing/blob/master/CONTRIBUTING.md)
- [Metadata for Integrations site and ArtifactHub](https://github.com/keptn-contrib/artifacthub).
- We have separate GitHub organizations for integration services
  - [keptn-contrib](https://github.com/keptn-contrib) contains stable services/integrations
  - [keptn-sandbox](https://github.com/keptn-sandbox) contains experimental services/integrations
- [Template for new integration services](https://github.com/keptn-sandbox/keptn-service-template-go)
- [Hosting new integrations and services](https://github.com/keptn-sandbox/contributing/blob/master/CONTRIBUTING.md).
  You can host your own integrations in the Keptn community!
