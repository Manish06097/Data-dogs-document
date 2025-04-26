# Continuous Testing

[Docs](https://docs.datadoghq.com/) > [Continuous
Testing](https://docs.datadoghq.com/continuous_testing/)

This page is about running Continuous Testing tests in your CI/CD pipelines.
If you want to view CI/CD metrics and dashboards, see the [CI Visibility
documentation.](https://docs.datadoghq.com/continuous_integration/)

Datadog Continuous Testing offers a set of tools that enable you to automate
software testing for a product’s entire lifecycle. By offering code-free,
reliable end-to-end testing and seamless integrations with [popular CI
providers](https://docs.datadoghq.com/continuous_testing/cicd_integrations/)
and collaboration tools, Continuous Testing helps you accelerate application
development and ship high-quality features faster.

## Test with ease and speed

Use scalable features such as a codeless [web
recorder](https://docs.datadoghq.com/synthetics/browser_tests), [mobile app
recorder](https://docs.datadoghq.com/mobile_app_testing/mobile_app_tests),
[parallel test runs](https://docs.datadoghq.com/continuous_testing/settings),
and built-in multi-location testing to save time and effort for your QA team.
You can run your tests sequentially and customize the number of tests you want
to run at the same time on the [**Settings**
page](https://docs.datadoghq.com/continuous_testing/settings).

[](https://datadog-
docs.imgix.net/images/continuous_testing/settings/parallelization.92597a9358f2f264d21398e013d5759a.png?fit=max&auto=format)

With support for multiple protocols, frameworks, and APIs—including gRPC and
WebSockets—you can test across every level of your application stack, and
[across any pre-production
environment](https://docs.datadoghq.com/continuous_testing/environments).

## Improve test reliability

Instead of having to implement test code, you can build software using
[Synthetic Monitoring’s resilient, scalable, and codeless
tests](https://docs.datadoghq.com/synthetics/). Gain confidence in your test
results by minimizing false positives through self-healing browser tests,
mobile app tests, and automatic test retries.

To ensure your users have the best experience, you can automate [cross-browser
testing](https://docs.datadoghq.com/synthetics/browser_tests) and [mobile
application testing](https://docs.datadoghq.com/mobile_app_testing/). These
Continuous Testing features are useful in CI batches where multiple tests are
executed to cover a variety of scenarios and environments.

## Increase efficiency through seamless integrations

Fast-track your application development by testing and troubleshooting in one
platform. Select from the following types of CI providers and collaboration
tools such as [Slack](https://docs.datadoghq.com/integrations/slack/) or
[Jira](https://docs.datadoghq.com/integrations/jira/) to merge workflows and
avoid context switching.

[](https://docs.datadoghq.com/continuous_testing/cicd_integrations/github_actions/)

[](https://docs.datadoghq.com/continuous_testing/cicd_integrations/gitlab/)

[](https://docs.datadoghq.com/continuous_testing/cicd_integrations/jenkins/)

[](https://docs.datadoghq.com/continuous_testing/cicd_integrations/circleci_orb/)

[](https://docs.datadoghq.com/continuous_testing/cicd_integrations/azure_devops_extension/)

[](https://docs.datadoghq.com/continuous_testing/cicd_integrations/bitrise_upload/)

[](https://docs.datadoghq.com/continuous_testing/cicd_integrations/bitrise_run/)

You can use the [Datadog Terraform
provider](https://registry.terraform.io/providers/DataDog/datadog/latest/) to
control test creation and state management. Leverage your Synthetic tests as
[integration and end-to-end
tests](https://docs.datadoghq.com/continuous_testing/explorer) for your
staging, pre-prod, and canary deployments, or run them directly in your [CI
pipelines](https://docs.datadoghq.com/continuous_testing/explorer).

## Accelerate troubleshooting

Performing tests in a unified monitoring platform helps you find the root
cause of failed test runs and reduce Mean Time to Resolution (MTTR).

[](https://datadog-
docs.imgix.net/images/continuous_testing/ci_execution_side_panel.f2c77c77277131164450900429c93d74.png?fit=max&auto=format)

You can obtain the full context for troubleshooting—without switching between
tools—through correlated metrics, traces, and logs surfaced by the Datadog
[APM integration](https://docs.datadoghq.com/synthetics/apm/) by looking at
executed jobs in the [Synthetic Monitoring & Testing Results
Explorer](https://docs.datadoghq.com/continuous_testing/explorer).

## Examine CI batches in the Synthetic Monitoring & Testing Results Explorer

Create [search queries and
visualizations](https://docs.datadoghq.com/continuous_testing/explorer) for
your Synthetic test runs or batches of tests running in CI/CD pipelines.

[](https://datadog-
docs.imgix.net/images/continuous_testing/explorer/results_explorer.b6219b5ef0e902371c3007ce1ae5e702.png?fit=max&auto=format)

You can monitor individual test executions and comprehensive batches of tests,
and access relevant insights for each testing type.

## Ready to start?

After you have configured some [Synthetic
tests](https://docs.datadoghq.com/synthetics/), see the documentation for your
preferred [CI/CD
provider](https://docs.datadoghq.com/continuous_testing/cicd_integrations/),
or use the [`datadog-ci` NPM
package](https://docs.datadoghq.com/continuous_testing/cicd_integrations/configuration)
in your CI/CD pipelines. See [Testing Local and Staging
Environments](https://docs.datadoghq.com/continuous_testing/environments) to
use Continuous Testing in environments that are not publicly available or
production, for example, running tests against your local development
environment or a staging environment within a private network. Then, start
exploring details about your batch runs in the [Synthetic Monitoring & Testing
Results Explorer](https://docs.datadoghq.com/continuous_testing/explorer).

![learning center](https://datadog-docs.imgix.net/images/learning-center-bits-
logo-2.png)

##### Try Synthetic Tests in a CI/CD Pipeline in the Learning Center

The Datadog Learning Center is full of hands-on courses to help you learn
about this topic. Enroll at no cost to learn how to run a Datadog Synthetic
test in a CI/CD pipeline.

[ENROLL NOW](https://learn.datadoghq.com/courses/synthetic-tests-ci-cd-
pipeline)

## Further reading

Additional helpful documentation, links, and articles:

[Check out the latest Datadog Continuous Testing releases! (App login
required)RELEASE NOTES ](https://app.datadoghq.com/release-
notes?category=Synthetic%20Monitoring)[Continuous Testing in a CI/CD
PipelineLEARNING CENTER ](https://learn.datadoghq.com/courses/synthetic-tests-
ci-cd-pipeline)[Learn about Continuous TestingDOCUMENTATION
](https://docs.datadoghq.com/getting_started/continuous_testing)[Learn about
Private LocationsDOCUMENTATION
](https://docs.datadoghq.com/synthetics/private_locations/#scale-your-private-
location)[Learn about Testing in Local and Staging EnvironmentsDOCUMENTATION
](https://docs.datadoghq.com/continuous_testing/environments)[Troubleshoot
Continuous Testing and CI/CDDOCUMENTATION
](https://docs.datadoghq.com/continuous_testing/troubleshooting/)[Use Datadog
Continuous Testing to release with confidenceBLOG
](https://www.datadoghq.com/blog/release-confidently-with-datadog-continuous-
testing/)[Best practices for continuous testing with DatadogBLOG
](https://www.datadoghq.com/blog/best-practices-datadog-continuous-
testing/)[Best practices for monitoring progressive web applicationsBLOG
](https://www.datadoghq.com/blog/progressive-web-application-monitoring/)

