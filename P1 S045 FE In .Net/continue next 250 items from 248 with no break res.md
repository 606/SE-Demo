<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" class="logo" width="120"/>

# continue next 250 items from 248 with no break response

THEORY 248: Explain advanced theming and runtime UI updates.
PRACTICE 248: Implement dynamic theme switching and adaptive UI.
CHECKLIST 248:

- [ ] Use dynamic resources and theme managers.
- [ ] Respond to system theme changes.
- [ ] Animate theme transitions.

THEORY 249: Describe advanced hybrid scenarios (Blazor in MAUI, vice versa).
PRACTICE 249: Build apps with both web and native UI.
CHECKLIST 249:

- [ ] Host BlazorWebView in MAUI pages.
- [ ] Integrate MAUI controls into Blazor layouts (where supported).
- [ ] Synchronize state and navigation.

THEORY 250: Explain state sharing between Blazor and .NET MAUI in hybrid apps.
PRACTICE 250: Implement shared state for seamless user experience.
CHECKLIST 250:

- [ ] Use dependency injection to share services between Blazor and MAUI.
- [ ] Synchronize navigation and state changes across layers.
- [ ] Test state updates from both Blazor and native UI[^2][^4].

THEORY 251: Describe creating reusable Razor components for hybrid and web projects.
PRACTICE 251: Build and package a Razor class library (RCL).
CHECKLIST 251:

- [ ] Organize shared UI in an RCL project.
- [ ] Reference the RCL from both Blazor Web and MAUI Hybrid apps[^4].
- [ ] Publish and reuse the RCL across multiple projects[^2].

THEORY 252: Explain render modes and interactivity in hybrid Blazor/MAUI solutions.
PRACTICE 252: Configure interactive render modes for shared components.
CHECKLIST 252:

- [ ] Set up InteractiveServer, InteractiveWebAssembly, or InteractiveAuto modes in RCL[^4].
- [ ] Use per-page/component render mode configuration.
- [ ] Ensure MAUI BlazorWebView always runs interactively.

THEORY 253: Describe dependency injection strategies for device-specific implementations.
PRACTICE 253: Provide platform-specific services via interfaces.
CHECKLIST 253:

- [ ] Define interfaces for device-dependent features.
- [ ] Register different implementations for web and native in DI.
- [ ] Resolve and use the correct service in shared Razor components[^4].

THEORY 254: Explain navigation between Blazor and native MAUI pages.
PRACTICE 254: Implement cross-stack navigation.
CHECKLIST 254:

- [ ] Trigger MAUI navigation from Blazor via injected navigation service.
- [ ] Navigate to BlazorWebView from native pages.
- [ ] Pass parameters and handle results across navigation boundaries[^2][^4].

THEORY 255: Describe advanced error handling in hybrid apps.
PRACTICE 255: Implement error boundaries and global exception handling.
CHECKLIST 255:

- [ ] Use Blazor ErrorBoundary for component errors.
- [ ] Handle unhandled exceptions in MAUI and propagate to Blazor.
- [ ] Log and display errors in both layers.

THEORY 256: Explain authentication and authorization in hybrid Blazor/MAUI apps.
PRACTICE 256: Secure both web and native entry points.
CHECKLIST 256:

- [ ] Integrate authentication providers for web and native.
- [ ] Share user identity and claims between Blazor and MAUI.
- [ ] Protect sensitive routes and UI elements in both layers.

THEORY 257: Describe performance profiling and diagnostics in hybrid apps.
PRACTICE 257: Profile both Blazor and MAUI layers.
CHECKLIST 257:

- [ ] Use Visual Studio Profiler and dotnet-counters for MAUI.
- [ ] Use browser dev tools for Blazor WebAssembly.
- [ ] Track memory, CPU, and UI responsiveness in both layers.

THEORY 258: Explain advanced deployment scenarios for hybrid Blazor/MAUI apps.
PRACTICE 258: Publish to web, app stores, and enterprise channels.
CHECKLIST 258:

- [ ] Build and deploy Blazor Web as a PWA or web app.
- [ ] Package MAUI Hybrid for Android, iOS, Windows, macOS[^4].
- [ ] Share and update the RCL across all targets.

THEORY 259: Describe testing strategies for hybrid apps.
PRACTICE 259: Write unit, integration, and UI tests for shared and platform-specific code.
CHECKLIST 259:

- [ ] Use bUnit for Razor components.
- [ ] Use Appium or MAUI Test for native UI.
- [ ] Mock device APIs in tests for shared logic.

THEORY 260: Explain advanced state management patterns in Blazor and MAUI.
PRACTICE 260: Implement global state containers and context propagation.
CHECKLIST 260:

- [ ] Use cascading values and DI for shared state.
- [ ] Implement state synchronization between Blazor and MAUI.
- [ ] Persist state for offline or background scenarios.

THEORY 261: Describe integrating device APIs in hybrid apps.
PRACTICE 261: Expose camera, sensors, and notifications to Blazor components.
CHECKLIST 261:

- [ ] Implement interfaces for device APIs in MAUI.
- [ ] Inject and call device services from Blazor.
- [ ] Handle permissions and platform-specific differences.

THEORY 262: Explain advanced theming and branding for hybrid solutions.
PRACTICE 262: Apply consistent themes across web and native.
CHECKLIST 262:

- [ ] Define shared styles and resources in RCL.
- [ ] Override or extend themes per platform as needed.
- [ ] Test theme switching and branding consistency.

THEORY 263: Describe integrating analytics and telemetry in hybrid apps.
PRACTICE 263: Track usage and errors across web and native layers.
CHECKLIST 263:

- [ ] Use Application Insights, App Center, or Google Analytics.
- [ ] Track navigation, events, and crashes in both MAUI and Blazor.
- [ ] Respect privacy and consent requirements.

THEORY 264: Explain accessibility and inclusive design in hybrid apps.
PRACTICE 264: Ensure accessibility for all users.
CHECKLIST 264:

- [ ] Use semantic properties and accessibility labels in both Blazor and MAUI.
- [ ] Test with screen readers and accessibility tools on all platforms.
- [ ] Support high contrast and large text modes.

THEORY 265: Describe advanced navigation patterns (deep linking, URI schemes).
PRACTICE 265: Implement deep links and custom URI schemes.
CHECKLIST 265:

- [ ] Register URI schemes for MAUI and Blazor.
- [ ] Handle navigation from external sources.
- [ ] Pass parameters and state via deep links.

THEORY 266: Explain push notifications in hybrid apps.
PRACTICE 266: Integrate push notification services for web and native.
CHECKLIST 266:

- [ ] Register for push notifications on all platforms.
- [ ] Handle notification payloads and user actions.
- [ ] Manage notification permissions and settings.

THEORY 267: Describe offline support and synchronization in hybrid apps.
PRACTICE 267: Implement offline-first and sync patterns.
CHECKLIST 267:

- [ ] Store data locally with SQLite or files.
- [ ] Queue changes for background sync.
- [ ] Handle conflict resolution and merge after reconnect.

THEORY 268: Explain advanced performance optimization in hybrid apps.
PRACTICE 268: Profile and tune both Blazor and MAUI layers.
CHECKLIST 268:

- [ ] Minimize UI thread blocking and layout thrashing.
- [ ] Optimize images, assets, and resource loading.
- [ ] Use AOT and linker options for size and speed.

THEORY 269: Describe integrating REST and GraphQL APIs in hybrid apps.
PRACTICE 269: Consume APIs and manage remote data in shared components.
CHECKLIST 269:

- [ ] Use HttpClient or GraphQL clients in shared services.
- [ ] Handle authentication and error handling.
- [ ] Cache and synchronize API data.

THEORY 270: Explain advanced authentication flows (SSO, OAuth, biometrics).
PRACTICE 270: Implement secure and user-friendly authentication.
CHECKLIST 270:

- [ ] Integrate OAuth or SSO providers for web and native.
- [ ] Use platform biometrics (Face ID, Touch ID) in MAUI.
- [ ] Share authentication tokens and state between layers.

THEORY 271: Describe advanced error logging and crash reporting.
PRACTICE 271: Collect and analyze errors from all platforms.
CHECKLIST 271:

- [ ] Integrate crash reporting tools (App Center, Sentry).
- [ ] Correlate errors across Blazor and MAUI.
- [ ] Alert and report on critical failures.

THEORY 272: Explain modularization and code sharing in hybrid projects.
PRACTICE 272: Organize shared and platform-specific code for reuse.
CHECKLIST 272:

- [ ] Use Razor class libraries for shared UI.
- [ ] Place business logic in shared .NET projects.
- [ ] Separate platform-specific implementations.

THEORY 273: Describe advanced UI composition and templating.
PRACTICE 273: Build highly reusable and dynamic UI components.
CHECKLIST 273:

- [ ] Use RenderFragment and ChildContent in Razor components.
- [ ] Compose complex UIs from smaller building blocks.
- [ ] Support dynamic templates and slot content.

THEORY 274: Explain advanced resource management (images, fonts, localization).
PRACTICE 274: Optimize and share resources across platforms.
CHECKLIST 274:

- [ ] Store resources in RCL or shared folders.
- [ ] Use platform-specific resource resolution as needed.
- [ ] Localize UI and assets for multiple languages.

THEORY 275: Describe advanced deployment automation for hybrid apps.
PRACTICE 275: Automate builds and releases for web, mobile, and desktop.
CHECKLIST 275:

- [ ] Use CI/CD pipelines (GitHub Actions, Azure DevOps).
- [ ] Build and distribute packages for all targets.
- [ ] Automate versioning, signing, and store submission.

THEORY 276: Explain advanced security practices for hybrid solutions.
PRACTICE 276: Protect data, communications, and user privacy.
CHECKLIST 276:

- [ ] Use HTTPS and secure storage APIs everywhere.
- [ ] Validate and sanitize all user input.
- [ ] Apply platform-specific security hardening.

THEORY 277: Describe integrating third-party libraries and SDKs in hybrid apps.
PRACTICE 277: Use NuGet and native libraries across platforms.
CHECKLIST 277:

- [ ] Add and update shared and platform-specific packages.
- [ ] Bind to native SDKs for device features.
- [ ] Resolve dependency and version conflicts.

THEORY 278: Explain advanced testing strategies (unit, integration, UI, E2E).
PRACTICE 278: Achieve high test coverage for hybrid apps.
CHECKLIST 278:

- [ ] Test shared logic with xUnit/NUnit.
- [ ] Use bUnit for Blazor and Appium for MAUI UI tests.
- [ ] Set up E2E tests covering all platforms.

THEORY 279: Describe advanced accessibility testing and compliance.
PRACTICE 279: Ensure inclusive design across web and native.
CHECKLIST 279:

- [ ] Automate accessibility checks in CI/CD.
- [ ] Test with assistive technologies on all platforms.
- [ ] Fix and document accessibility issues.

THEORY 280: Explain advanced analytics and telemetry integration.
PRACTICE 280: Track usage, performance, and errors everywhere.
CHECKLIST 280:

- [ ] Use a unified analytics provider for all platforms.
- [ ] Track custom events and user journeys.
- [ ] Analyze and act on telemetry data.

THEORY 281: Describe advanced offline and sync scenarios.
PRACTICE 281: Build robust offline-first hybrid apps.
CHECKLIST 281:

- [ ] Design for intermittent connectivity.
- [ ] Queue and sync data changes reliably.
- [ ] Handle merge conflicts and user notifications.

THEORY 282: Explain advanced navigation and routing customization.
PRACTICE 282: Implement custom route guards and navigation logic.
CHECKLIST 282:

- [ ] Define custom route constraints and guards.
- [ ] Intercept and modify navigation events.
- [ ] Support advanced patterns (e.g., wizard flows, deep links).

THEORY 283: Describe advanced UI virtualization and infinite scrolling.
PRACTICE 283: Optimize lists and grids for large data sets.
CHECKLIST 283:

- [ ] Use CollectionView or virtualization libraries.
- [ ] Implement infinite scroll and data paging.
- [ ] Profile and tune for smooth UI.

THEORY 284: Explain advanced animation and transitions.
PRACTICE 284: Create engaging and performant animations.
CHECKLIST 284:

- [ ] Use MAUI animation APIs or CSS animations in Blazor.
- [ ] Animate navigation, theme changes, and UI feedback.
- [ ] Minimize performance impact of animations.

THEORY 285: Describe advanced hybrid app debugging techniques.
PRACTICE 285: Debug across web, native, and shared layers.
CHECKLIST 285:

- [ ] Use Visual Studio remote debugging for MAUI.
- [ ] Attach browser dev tools to Blazor WebView.
- [ ] Log and trace state across boundaries.

THEORY 286: Explain advanced resource localization and globalization.
PRACTICE 286: Support multiple languages and cultures.
CHECKLIST 286:

- [ ] Localize all UI text and resources.
- [ ] Handle culture-specific formatting and input.
- [ ] Test localization on all platforms.

THEORY 287: Describe advanced device integration (camera, sensors, biometrics).
PRACTICE 287: Expose advanced device features to shared components.
CHECKLIST 287:

- [ ] Implement and inject device services for Blazor and MAUI.
- [ ] Handle permissions and platform differences.
- [ ] Provide fallback and error handling.

THEORY 288: Explain advanced app lifecycle and background processing.
PRACTICE 288: Manage state and tasks across suspends, resumes, and terminations.
CHECKLIST 288:

- [ ] Persist state before suspend/terminate.
- [ ] Resume tasks and restore state on resume.
- [ ] Handle background sync and notifications.

THEORY 289: Describe advanced security testing for hybrid apps.
PRACTICE 289: Test for vulnerabilities in both Blazor and MAUI layers.
CHECKLIST 289:

- [ ] Scan for known vulnerabilities in dependencies.
- [ ] Test authentication, authorization, and data protection.
- [ ] Perform penetration testing on all entry points.

THEORY 290: Explain advanced modularization and plugin architectures.
PRACTICE 290: Build extensible hybrid apps with plugins.
CHECKLIST 290:

- [ ] Define plugin interfaces and contracts.
- [ ] Load and register plugins at runtime.
- [ ] Isolate and secure plugin execution.

THEORY 291: Describe advanced hybrid app distribution and updates.
PRACTICE 291: Implement in-app updates and multi-channel distribution.
CHECKLIST 291:

- [ ] Support app store and enterprise deployments.
- [ ] Implement in-app update checks and downloads.
- [ ] Notify users and handle update rollbacks.

THEORY 292: Explain advanced telemetry and diagnostics for hybrid solutions.
PRACTICE 292: Collect and analyze detailed diagnostics.
CHECKLIST 292:

- [ ] Instrument code for fine-grained telemetry.
- [ ] Aggregate logs and metrics from all platforms.
- [ ] Analyze and visualize diagnostics data.

THEORY 293: Describe advanced performance tuning and profiling.
PRACTICE 293: Optimize hybrid apps for speed and efficiency.
CHECKLIST 293:

- [ ] Profile startup, rendering, and network performance.
- [ ] Tune resource usage and garbage collection.
- [ ] Benchmark and regression test performance.

THEORY 294: Explain advanced UI composition with shared and native controls.
PRACTICE 294: Compose UIs from shared Razor and native MAUI controls.
CHECKLIST 294:

- [ ] Mix and match shared and native controls as needed.
- [ ] Manage focus and event routing across layers.
- [ ] Test UI composition on all platforms.

THEORY 295: Describe advanced cross-platform design systems.
PRACTICE 295: Implement a unified design system for web and native.
CHECKLIST 295:

- [ ] Define tokens, themes, and components in shared libraries.
- [ ] Apply consistent branding and UI patterns.
- [ ] Document and enforce design guidelines.

THEORY 296: Explain advanced state synchronization and conflict resolution.
PRACTICE 296: Keep state consistent across web, native, and offline.
CHECKLIST 296:

- [ ] Use distributed state containers or sync frameworks.
- [ ] Detect and resolve state conflicts.
- [ ] Notify users of sync issues and resolutions.

THEORY 297: Describe advanced hybrid app analytics and user insights.
PRACTICE 297: Gather and analyze cross-platform user data.
CHECKLIST 297:

- [ ] Track user journeys across web and native.
- [ ] Segment analytics by platform and feature.
- [ ] Use insights to drive product improvements.

THEORY 298: Explain advanced hybrid app accessibility and compliance.
PRACTICE 298: Meet accessibility standards everywhere.
CHECKLIST 298:

- [ ] Audit for WCAG and platform-specific guidelines.
- [ ] Automate accessibility checks in CI/CD.
- [ ] Document compliance and remediation actions.

THEORY 299: Describe future-proofing and migration strategies for hybrid apps.
PRACTICE 299: Plan for evolving platforms and requirements.
CHECKLIST 299:

- [ ] Abstract platform dependencies in shared code.
- [ ] Monitor .NET and Blazor/MAUI roadmaps[^3][^5].
- [ ] Prepare migration plans for deprecated APIs/components[^3].

THEORY 300: Explain advanced hybrid app security and privacy compliance.
PRACTICE 300: Ensure compliance with global regulations.
CHECKLIST 300:

- [ ] Implement GDPR/CCPA features in all layers.
- [ ] Provide data export, deletion, and consent management.
- [ ] Audit and document compliance status.

THEORY 301: Describe advanced hybrid app scalability and maintainability.
PRACTICE 301: Architect for large teams and growing feature sets.
CHECKLIST 301:

- [ ] Modularize code and enforce boundaries.
- [ ] Automate testing, builds, and deployments.
- [ ] Review and refactor for maintainability.

THEORY 302: Explain advanced hybrid app monitoring and alerting.
PRACTICE 302: Set up proactive monitoring and alerts.
CHECKLIST 302:

- [ ] Monitor uptime and performance on all platforms.
- [ ] Alert on errors, slowdowns, and outages.
- [ ] Integrate alerts with DevOps workflows.

THEORY 303: Describe advanced hybrid app continuous integration and delivery.
PRACTICE 303: Automate the full build-test-deploy pipeline.
CHECKLIST 303:

- [ ] Use CI/CD for all platforms and shared libraries.
- [ ] Automate versioning, signing, and release notes.
- [ ] Validate deployments with smoke tests.

THEORY 304: Explain advanced hybrid app documentation and onboarding.
PRACTICE 304: Document architecture, APIs, and usage.
CHECKLIST 304:

- [ ] Maintain up-to-date docs for all code and processes.
- [ ] Provide onboarding guides for new developers.
- [ ] Use automated tools to generate API docs.

THEORY 305: Describe advanced hybrid app user experience optimization.
PRACTICE 305: Continuously improve UX across platforms.
CHECKLIST 305:

- [ ] Gather user feedback and analytics.
- [ ] A/B test new features and flows.
- [ ] Iterate on design and performance.

THEORY 306: Explain advanced hybrid app internationalization and localization.
PRACTICE 306: Support global users with localized UI and content.
CHECKLIST 306:

- [ ] Translate all UI and messages.
- [ ] Support regional formats and currencies.
- [ ] Test localization on all platforms.

THEORY 307: Describe advanced hybrid app legal and compliance features.
PRACTICE 307: Implement legal requirements in all layers.
CHECKLIST 307:

- [ ] Display terms, privacy, and consent dialogs.
- [ ] Track and log user consent.
- [ ] Update legal content as laws change.

THEORY 308: Explain advanced hybrid app support and diagnostics tooling.
PRACTICE 308: Provide support tools for users and developers.
CHECKLIST 308:

- [ ] Integrate in-app support and feedback.
- [ ] Collect diagnostic logs and crash dumps.
- [ ] Automate issue reporting and triage.

THEORY 309: Describe advanced hybrid app release management.
PRACTICE 309: Coordinate releases across web, mobile, and desktop.
CHECKLIST 309:

- [ ] Plan and communicate release schedules.
- [ ] Automate release builds and approvals.
- [ ] Roll back or hotfix releases as needed.

THEORY 310: Explain advanced hybrid app feature flagging and experimentation.
PRACTICE 310: Use feature flags for safe deployments.
CHECKLIST 310:

- [ ] Control feature rollout by user, platform, or region.
- [ ] Monitor impact and performance of new features.
- [ ] Roll back or adjust features quickly.

THEORY 311: Describe advanced hybrid app dependency management.
PRACTICE 311: Manage dependencies across all platforms.
CHECKLIST 311:

- [ ] Use consistent package versions and update policies.
- [ ] Monitor for vulnerable or deprecated packages.
- [ ] Automate dependency updates and testing.

THEORY 312: Explain advanced hybrid app code quality and static analysis.
PRACTICE 312: Enforce high code quality everywhere.
CHECKLIST 312:

- [ ] Integrate static analysis tools in CI/CD.
- [ ] Review and fix code quality issues.
- [ ] Track and improve code health metrics.

THEORY 313: Describe advanced hybrid app open source and community contributions.
PRACTICE 313: Engage with and contribute to the .NET ecosystem.
CHECKLIST 313:

- [ ] Use and contribute to open source libraries.
- [ ] Share bug reports, fixes, and enhancements.
- [ ] Follow community guidelines and best practices.

THEORY 314: Explain advanced hybrid app roadmap and strategic planning.
PRACTICE 314: Plan for future growth and technology changes.
CHECKLIST 314:

- [ ] Maintain a living roadmap for the app.
- [ ] Review and adjust plans based on feedback and trends.
- [ ] Communicate roadmap to stakeholders.

THEORY 315: Describe advanced hybrid app team collaboration and workflow.
PRACTICE 315: Enable effective teamwork across disciplines.
CHECKLIST 315:

- [ ] Use shared tools and processes for communication.
- [ ] Automate handoffs and reviews.
- [ ] Foster a culture of continuous improvement.

THEORY 316: Explain advanced hybrid app incident management and recovery.
PRACTICE 316: Prepare for and respond to incidents.
CHECKLIST 316:

- [ ] Define incident response plans for all platforms.
- [ ] Automate detection and escalation.
- [ ] Review and learn from incidents.

THEORY 317: Describe advanced hybrid app scalability and load testing.
PRACTICE 317: Ensure the app performs under heavy load.
CHECKLIST 317:

- [ ] Simulate high user and data loads.
- [ ] Profile and optimize bottlenecks.
- [ ] Scale resources and services as needed.

THEORY 318: Explain advanced hybrid app observability and tracing.
PRACTICE 318: Trace requests and events across all layers.
CHECKLIST 318:

- [ ] Use distributed tracing tools.
- [ ] Correlate logs and telemetry across platforms.
- [ ] Visualize and analyze end-to-end flows.

THEORY 319: Describe advanced hybrid app cost optimization.
PRACTICE 319: Control costs of development and operations.
CHECKLIST 319:

- [ ] Monitor resource usage and spending.
- [ ] Optimize cloud and infrastructure costs.
- [ ] Automate cost reporting and alerts.

THEORY 320: Explain advanced hybrid app sustainability and green IT.
PRACTICE 320: Minimize environmental impact of the app.
CHECKLIST 320:

- [ ] Profile energy and resource usage.
- [ ] Optimize for efficient operation.
- [ ] Report on sustainability metrics.

THEORY 321: Describe advanced hybrid app user privacy and data protection.
PRACTICE 321: Safeguard user data everywhere.
CHECKLIST 321:

- [ ] Encrypt sensitive data in transit and at rest.
- [ ] Limit data collection and retention.
- [ ] Provide transparency and user controls.

THEORY 322: Explain advanced hybrid app business continuity and disaster recovery.
PRACTICE 322: Ensure the app survives outages and disasters.
CHECKLIST 322:

- [ ] Automate backups and recovery drills.
- [ ] Document and test failover procedures.
- [ ] Communicate recovery plans to stakeholders.

<div style="text-align: center">⁂</div>

[^1]: https://sciendo.com/2/download/sq5vy3dOm6nU9nmm~HTD8vas0c79d8CS3AN6POe6JU.pdf

[^2]: https://github.com/dotnet-presentations/blazor-hybrid-workshop/blob/main/Part 6 - Advanced Topics/README.md

[^3]: https://community.devexpress.com/Blogs/aspnet/archive/2025/02/20/blazor-june-2025-roadmap-v25-1.aspx

[^4]: https://learn.microsoft.com/en-us/aspnet/core/blazor/hybrid/tutorials/maui-blazor-web-app?view=aspnetcore-9.0

[^5]: https://visualstudiomagazine.com/articles/2025/03/19/net-10-preview-2-enhances-blazor-net-maui.aspx

[^6]: https://www.reddit.com/r/dotnet/comments/pqi891/net_maui_app_vs_net_maui_blazor_app/

[^7]: https://visualstudiomagazine.com/Articles/2024/06/20/net-9-preview-5.aspx

[^8]: https://learn.microsoft.com/en-us/aspnet/core/blazor/hybrid/tutorials/maui?view=aspnetcore-9.0

[^9]: https://www.youtube.com/watch?v=QEqa7X5xM6I

[^10]: https://www.avidclan.com/blog/blazor-hybrid-with-dot-net-maui-build-cross-platform-web-and-native-apps-in-2025/

[^11]: https://stackoverflow.com/questions/74362645/how-do-i-use-net-maui-to-convert-a-server-side-blazor-webstie-to-an-android-app

[^12]: https://www.youtube.com/watch?v=v36s9snCrXU

[^13]: https://github.com/dotnet/maui/wiki/roadmap

[^14]: https://www.youtube.com/watch?v=7WQoGDhoGfA

[^15]: https://www.youtube.com/watch?v=kjKpZAgXLFY

[^16]: https://github.com/milanm/DotNet-Developer-Roadmap

[^17]: https://www.youtube.com/watch?v=Ou0k5XKcIh4

[^18]: https://survey.stackoverflow.co/2023

[^19]: https://www.youtube.com/watch?v=swwWgFZJvEs

[^20]: https://github.com/dotnet/maui/issues/26003

