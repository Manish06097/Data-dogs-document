# RUM & Session Replay

[Docs](https://docs.datadoghq.com/) > [RUM & Session
Replay](https://docs.datadoghq.com/real_user_monitoring/)

##### Join an enablement webinar session

Discover how to create custom user actions tailored to specific business
needs, enabling precise tracking of user behavior.

[SIGN UP](https://www.datadoghq.com/technical-
enablement/sessions/?tags.topics-0=RUM)

## What is Real User Monitoring?

[](https://datadog-docs.imgix.net/images/real_user_monitoring/performance-
summary-browser.ba22e1a210fc9f66622ac32f70f42634.png?fit=max&auto=format)

Datadog’s _Real User Monitoring (RUM)_ gives you end-to-end visibility into
the real-time activity and experience of individual users. RUM solves four
types of use cases for monitoring web and mobile applications:

  * **Performance** : Track the performance of web pages, mobile application screens, user actions, network requests, and your frontend code.
  * **Error Management** : Monitor the ongoing bugs and issues and track them over time and versions.
  * **Analytics / Usage** : Understand who is using your application (country, device, OS), monitor individual users journeys, and analyze how users interact with your application (most common page visited, clicks, interactions, and feature usage).
  * **Support** : Retrieve all of the information related to one user session to troubleshoot an issue (session duration, pages visited, interactions, resources loaded, and errors).

A user session is a user journey on your web or mobile application lasting up
to four hours. A session usually includes pageviews and associated telemetry.
If a user does not interact with an application for 15 minutes, the session is
considered complete. A new session starts when the user interacts with the
application again.

## What is Session Replay?

Datadog’s _Session Replay_ allows you to capture and visually replay the web
browsing experience of your users.

Combined with RUM performance data, Session Replay is beneficial for error
identification, reproduction, and resolution, and provides insights into your
web application’s usage patterns and design pitfalls.

## Get started

Select an application type to start collecting RUM data:

[](https://docs.datadoghq.com/real_user_monitoring/browser/)

[](https://docs.datadoghq.com/real_user_monitoring/mobile_and_tv_monitoring/android/setup)

[](https://docs.datadoghq.com/real_user_monitoring/mobile_and_tv_monitoring/ios/setup)

[](https://docs.datadoghq.com/real_user_monitoring/mobile_and_tv_monitoring/react_native/setup)

[](https://docs.datadoghq.com/real_user_monitoring/mobile_and_tv_monitoring/flutter/setup)

[](https://docs.datadoghq.com/real_user_monitoring/mobile_and_tv_monitoring/android/setup)

[](https://docs.datadoghq.com/real_user_monitoring/mobile_and_tv_monitoring/ios/setup)

[](https://docs.datadoghq.com/real_user_monitoring/mobile_and_tv_monitoring/roku/setup)

[](https://docs.datadoghq.com/real_user_monitoring/mobile_and_tv_monitoring/setup/unity/)

[](https://docs.datadoghq.com/real_user_monitoring/mobile_and_tv_monitoring/setup/kotlin_multiplatform/)

### Capabilities and platform support

**Note** : The Datadog Flutter SDK is not supported for MacOS, Windows, or
Linux.

The following table shows which RUM capabilities are supported on each
platform:

Feature| Browser| Android| iOS| Flutter| React Native| Roku| Notes  
---|---|---|---|---|---|---|---  
Send logs to Datadog|  __| __| __| __| __| __|  
Distributed tracing of network requests|  __| __| __| __| __| __| The**Datadog
Roku SDK** is only able to track some types of HTTP requests.  
Track Views and Actions (RUM)| __| __| __| __| __| __| \- All actions tracked
in**Flutter Web** are recorded as `custom`  
\- **Roku** supports only manual action tracking.  
Feature Flags tracking and release tracking|  __| __| __| __| __| |   
Error tracking and source mapping|  __| __| __| __| __| __| Only partially
supported for**React Native**  
Crash tracking, symbolication, and deobfuscation|  __| __| __| __| __| __|  
Stop sessions (Kiosk Monitoring)| __| __| __| __| __| |   
Track Events in WebViews| |  __| __| __| __| |   
Monitor platform-specific vitals|  __| __| __| __| __| |   
Global context/attribute tracking in Logs|  __| | | | | |   
Client side tracing| |  __| __| | | |   
Session Replay|  __| __| __| | | | Mobile Session Replay is in Preview for native mobile apps.  
Frustration signals|  __| __| __| __| __| __| Only partially supported for
all**mobile** and **Roku** devices  
  
## Supported endpoints for SDK domains

All Datadog SDKs traffic is transmitted over SSL (default 443) to the
following domains:

Site| Site URL  
---|---  
US1| `https://browser-intake-datadoghq.com`  
US3| `https://browser-intake-us3-datadoghq.com`  
US5| `https://browser-intake-us5-datadoghq.com`  
EU1| `https://browser-intake-datadoghq.eu`  
US1-FED| `https://browser-intake-ddog-gov.com`  
AP1| `https://browser-intake-ap1-datadoghq.com`  
  
## Explore Datadog RUM

Access RUM by navigating to [**Digital Experience > Performance
Summary**](https://app.datadoghq.com/rum/performance-monitoring).

Select an application from the top navigation, or follow the setup
instructions for
[browser](https://docs.datadoghq.com/real_user_monitoring/browser/setup/) or
[mobile](https://docs.datadoghq.com/real_user_monitoring/mobile_and_tv_monitoring/)
to add your first application.

[](https://datadog-docs.imgix.net/images/real_user_monitoring/rum-performance-
application-selector.c4338a455c1dd29329e37c255ef59b73.png?fit=max&auto=format)

**Tip** : To open RUM from Datadog’s global search, press `Cmd`/`Ctrl` \+ `K`
and search for `real user monitoring`.

## Performance monitoring summary

Browser Performance Summary| Mobile Performance Summary  
---|---  
[](https://datadog-docs.imgix.net/images/real_user_monitoring/performance-
summary-browser.ba22e1a210fc9f66622ac32f70f42634.png?fit=max&auto=format)|
[](https://datadog-docs.imgix.net/images/real_user_monitoring/performance-
summary-mobile-2.753130f48e10dd97d00bbef53c8e51b1.png?fit=max&auto=format)  
  
The [RUM Performance Monitoring
summary](https://app.datadoghq.com/rum/performance-monitoring) page provides
relevant and actionable insights for both web and mobile applications. You
have a tailored experience for each platform that helps you:

  * **Focus on key data points** by platform, such as the UI latency for web or mobile crashes
  * **Monitor application health** through familiar KPIs, such as Core Web Vitals for web apps or hang rate for iOS, to assess app reliability
  * **Dive into investigations directly** from interactive widgets without leaving the page

For **web apps** , use the search bar to filter data, identify slow pages, and
follow the UI to the [RUM Optimization
Inspect](https://app.datadoghq.com/rum/optimization/inspect) page.

For **mobile apps** , review recent crashes at the bottom of the page and use
the [Error
Tracking](https://docs.datadoghq.com/real_user_monitoring/error_tracking/)
side panel for troubleshooting.

### Out-of-the-box dashboards

Analyze information about your user sessions, performance, mobile
applications, frustration signals, network resources, and errors collected
automatically with [out-of-the-box RUM
dashboards](https://docs.datadoghq.com/real_user_monitoring/platform/dashboards/).

[](https://datadog-docs.imgix.net/images/real_user_monitoring/rum-out-of-the-
box-dashboard.0e6c161abcc5f3b87cf472e785740a17.png?fit=max&auto=format)

### RUM Explorer and visualizations

View user sessions in segments, such as checking when latency impacts your
premium customers, with
[visualizations](https://docs.datadoghq.com/real_user_monitoring/explorer/visualize/).
Explore data, save views, and create
[monitors](https://docs.datadoghq.com/monitors/types/real_user_monitoring/) on
your customized searches.

### Integration with logs, APM, and profiler

View your [backend traces, logs, and infrastructure
metrics](https://docs.datadoghq.com/real_user_monitoring/correlate_with_other_telemetry/apm/)
down to the exact line of code impacting your application performance,
corresponding to user experiences and reported issues.

[](https://datadog-
docs.imgix.net/images/real_user_monitoring/connect_rum_and_traces/rum_apm_logs-2.37d045abf254c97fe68ea022b0693385.png?fit=max&auto=format)

### Error tracking and crash reporting

Get automated alerts on outliers and groups of errors, timeouts, and crashes
to significantly reduce your MTTR with [Error
Tracking](https://docs.datadoghq.com/real_user_monitoring/error_tracking/).

### Web and mobile vitals

View performance scores and telemetry for [browser
applications](https://docs.datadoghq.com/real_user_monitoring/browser/monitoring_page_performance/#event-
timings-and-core-web-vitals) such as Core Web Vitals and Mobile Vitals for
[iOS and
tvOS](https://docs.datadoghq.com/real_user_monitoring/ios/mobile_vitals/) or
[Android and Android TV
applications](https://docs.datadoghq.com/real_user_monitoring/android/mobile_vitals/).

### Web view tracking

Collect information from your native web applications and explore hybrid views
with Web View Tracking for [iOS and
tvOS](https://docs.datadoghq.com/real_user_monitoring/ios/web_view_tracking/)
or [Android and Android
TV](https://docs.datadoghq.com/real_user_monitoring/android/web_view_tracking/).

[](https://datadog-
docs.imgix.net/images/real_user_monitoring/webview_tracking/webview_tracking_light.9f5964c2c9aa95f9bccb790a1fd51bf3.png?fit=max&auto=format)

## Explore Datadog Session Replay

### Session replays

Watch [browser
recordings](https://docs.datadoghq.com/real_user_monitoring/session_replay/browser/)
of real users interacting with your website and set [privacy
controls](https://docs.datadoghq.com/real_user_monitoring/session_replay/browser/privacy_options/)
for your organization.

### Developer tools

Access triggered logs, errors, and performance information when
troubleshooting application issues using [Browser Dev
Tools](https://docs.datadoghq.com/real_user_monitoring/session_replay/browser/developer_tools/).

## Permissions

Granular access control for RUM is in Preview.

By default, all users can change an application’s RUM configuration.

Use granular access controls to limit the
[roles](https://docs.datadoghq.com/account_management/rbac/) that may edit a
particular application’s RUM configuration:

  1. While viewing an application’s RUM configuration, click on the **Edit application** button at the top of the screen. A dropdown appears.
  2. Select **Manage App Permissions**.
  3. Click **Restrict Access**.
  4. The dialog box updates to show that members of your organization have **Viewer** access by default.
  5. Use the dropdown to select one or more roles, teams, or users that may edit the notebook.
  6. Click **Add**.
  7. The dialog box updates to show that the role you selected has the **Editor** permission.
  8. Click **Save**.

**Note:** To maintain your edit access to the application, the system requires
you to include at least one role that you are a member of before saving.

You must have edit access to restore general access to a restricted
application. Complete the following steps:

  1. While viewing an application’s RUM configuration, click on the **Edit application** button at the top of the screen. A dropdown appears.
  2. Select **Manage App Permissions**.
  3. Click **Restore Full Access**.
  4. Click **Save**.

## Further reading

Additional helpful documentation, links, and articles:

[Check out the latest Datadog RUM releases! (App login required)RELEASE NOTES
](https://app.datadoghq.com/release-
notes?category=Real%20User%20Monitoring)[Join an interactive session to gain
insights through Real User MonitoringFOUNDATION ENABLEMENT
](https://dtdg.co/fe)[Introducing Datadog Real User MonitoringBLOG
](https://www.datadoghq.com/blog/real-user-monitoring-with-datadog/)[Improve
mobile user experience with Datadog Mobile Real User MonitoringBLOG
](https://www.datadoghq.com/blog/datadog-mobile-rum/)[Best practices for
monitoring mobile app performanceBLOG ](https://www.datadoghq.com/blog/mobile-
monitoring-best-practices/)[Make sense of application issues with Datadog
Error TrackingBLOG ](https://www.datadoghq.com/blog/error-tracking/)[Unify APM
and RUM data for full-stack visibilityBLOG
](https://www.datadoghq.com/blog/unify-apm-rum-datadog/)[Use geomaps to
visualize your app data by locationBLOG
](https://www.datadoghq.com/blog/datadog-geomaps/)[Get better RUM data with
our custom React componentsBLOG ](https://www.datadoghq.com/blog/datadog-rum-
react-components/#tune-up-your-react-data-collection)[Monitor your hybrid
mobile applications with DatadogBLOG ](https://www.datadoghq.com/blog/hybrid-
app-monitoring/)[How Datadog's Technical Solutions team uses RUM, Session
Replay, and Error Tracking to resolve customer issuesBLOG
](https://www.datadoghq.com/blog/how-datadogs-tech-solutions-team-rum-session-
replay/)[Best practices for monitoring static web applicationsBLOG
](https://www.datadoghq.com/blog/static-web-application-monitoring-best-
practices/)[RUM Browser Data CollectedDOCUMENTATION
](https://docs.datadoghq.com/real_user_monitoring/browser/data_collected/)[Best
practices for monitoring progressive web applicationsBLOG
](https://www.datadoghq.com/blog/progressive-web-application-monitoring/)

