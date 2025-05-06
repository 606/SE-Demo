<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" class="logo" width="120"/>

## Frontend Development with .NET (Blazor \& .NET MAUI) - Atomic Breakdown (0–250)

**Progression Check:**
You have completed all core .NET backend, testing, and security topics. Next, per the roadmap, is Frontend Development with .NET, focusing on Blazor (WebAssembly \& Server) and .NET MAUI.

---

### Blazor Fundamentals

**THEORY 0:** Explain the purpose and architecture of Blazor in .NET.
**PRACTICE 0:** Diagram Blazor Server vs. Blazor WebAssembly hosting models.
**CHECKLIST 0:**

- [ ] Identify Blazor’s role in .NET frontend development.
- [ ] Compare Blazor Server and WASM architectures.
- [ ] List scenarios for each hosting model.

**THEORY 1:** Describe the Blazor component model.
**PRACTICE 1:** Build a simple Blazor component.
**CHECKLIST 1:**

- [ ] Use `.razor` files for components.
- [ ] Define parameters and event callbacks.
- [ ] Render components in a Blazor app.

**THEORY 2:** Explain Razor syntax and directives.
**PRACTICE 2:** Use Razor syntax for data binding and conditional rendering.
**CHECKLIST 2:**

- [ ] Use `@code`, `@functions`, and `@inject`.
- [ ] Implement `@if`, `@foreach`, and `@bind`.
- [ ] Use partial classes for code-behind.

**THEORY 3:** Describe component parameters and cascading values.
**PRACTICE 3:** Pass data between parent and child components.
**CHECKLIST 3:**

- [ ] Use `[Parameter]` and `[CascadingParameter]`.
- [ ] Bind values from parent to child.
- [ ] Use cascading values for shared state.

**THEORY 4:** Explain event handling in Blazor.
**PRACTICE 4:** Implement button click and form submit events.
**CHECKLIST 4:**

- [ ] Use `@onclick`, `@onchange`, and other event handlers.
- [ ] Pass event arguments to handlers.
- [ ] Prevent default and stop propagation.

**THEORY 5:** Describe data binding in Blazor.
**PRACTICE 5:** Use one-way and two-way binding.
**CHECKLIST 5:**

- [ ] Use `@bind` for two-way binding.
- [ ] Use `@value` for one-way binding.
- [ ] Bind to input, select, and custom components.

**THEORY 6:** Explain dependency injection in Blazor.
**PRACTICE 6:** Inject and use services in components.
**CHECKLIST 6:**

- [ ] Register services in `Program.cs` or `Startup.cs`.
- [ ] Use `@inject` or `[Inject]` to access services.
- [ ] Demonstrate singleton, scoped, and transient lifetimes.

**THEORY 7:** Describe routing in Blazor applications.
**PRACTICE 7:** Configure and use Blazor routing.
**CHECKLIST 7:**

- [ ] Use `@page` directive.
- [ ] Navigate with `NavLink` and `NavigationManager`.
- [ ] Handle route parameters and constraints.

**THEORY 8:** Explain forms and validation in Blazor.
**PRACTICE 8:** Create forms with validation.
**CHECKLIST 8:**

- [ ] Use `EditForm`, `InputText`, `InputSelect`, etc.
- [ ] Apply data annotations for validation.
- [ ] Show validation messages.

**THEORY 9:** Describe state management in Blazor.
**PRACTICE 9:** Implement state sharing between components.
**CHECKLIST 9:**

- [ ] Use cascading values and dependency injection.
- [ ] Implement in-memory state containers.
- [ ] Discuss limitations and persistence strategies.

**THEORY 10:** Explain JavaScript interop in Blazor.
**PRACTICE 10:** Call JavaScript from .NET and vice versa.
**CHECKLIST 10:**

- [ ] Use `IJSRuntime` for invoking JS.
- [ ] Register .NET methods for JS to call.
- [ ] Pass data between JS and .NET.

**THEORY 11:** Describe Blazor component lifecycle.
**PRACTICE 11:** Use lifecycle methods in components.
**CHECKLIST 11:**

- [ ] Implement `OnInitialized`, `OnParametersSet`, `OnAfterRender`.
- [ ] Handle async initialization.
- [ ] Clean up with `Dispose`.

**THEORY 12:** Explain layout and templating in Blazor.
**PRACTICE 12:** Create and use layouts and templates.
**CHECKLIST 12:**

- [ ] Define layout components with `@layout`.
- [ ] Use `RenderFragment` for templates.
- [ ] Nest layouts and templates.

**THEORY 13:** Describe error handling and diagnostics in Blazor.
**PRACTICE 13:** Implement error boundaries and logging.
**CHECKLIST 13:**

- [ ] Use `ErrorBoundary` component.
- [ ] Log errors to browser or server.
- [ ] Handle unhandled exceptions gracefully.

**THEORY 14:** Explain authentication and authorization in Blazor.
**PRACTICE 14:** Secure Blazor apps with built-in auth.
**CHECKLIST 14:**

- [ ] Use `[Authorize]` and `AuthorizeView`.
- [ ] Integrate with ASP.NET Core Identity or external providers.
- [ ] Handle login, logout, and user claims.

**THEORY 15:** Describe publishing and deployment of Blazor apps.
**PRACTICE 15:** Deploy Blazor WebAssembly and Server apps.
**CHECKLIST 15:**

- [ ] Publish to static hosting (WASM) or ASP.NET Core host (Server).
- [ ] Configure base paths and environment settings.
- [ ] Optimize for production (linking, compression).

---

### .NET MAUI Fundamentals

**THEORY 16:** Explain the architecture and purpose of .NET MAUI.
**PRACTICE 16:** Diagram .NET MAUI’s cross-platform model.
**CHECKLIST 16:**

- [ ] List supported platforms (Android, iOS, Windows, macOS).
- [ ] Describe single-project structure.
- [ ] Compare MAUI to Xamarin.Forms.

**THEORY 17:** Describe the MAUI app lifecycle.
**PRACTICE 17:** Implement lifecycle event handlers.
**CHECKLIST 17:**

- [ ] Use `OnStart`, `OnSleep`, `OnResume`.
- [ ] Handle platform-specific lifecycle events.
- [ ] Manage background/foreground transitions.

**THEORY 18:** Explain XAML and code-behind in MAUI.
**PRACTICE 18:** Build a simple MAUI page with XAML.
**CHECKLIST 18:**

- [ ] Define UI with XAML.
- [ ] Handle events in code-behind.
- [ ] Use data binding in XAML.

**THEORY 19:** Describe navigation in MAUI applications.
**PRACTICE 19:** Implement navigation between pages.
**CHECKLIST 19:**

- [ ] Use `NavigationPage` and `Shell`.
- [ ] Pass parameters between pages.
- [ ] Handle modal and stack navigation.

**THEORY 20:** Explain data binding and MVVM in MAUI.
**PRACTICE 20:** Implement MVVM pattern in a MAUI app.
**CHECKLIST 20:**

- [ ] Create ViewModels and bind to Views.
- [ ] Use `INotifyPropertyChanged`.
- [ ] Bind commands to UI actions.

**THEORY 21:** Describe dependency injection in MAUI.
**PRACTICE 21:** Register and resolve services in MAUI.
**CHECKLIST 21:**

- [ ] Use built-in DI container.
- [ ] Register platform-specific services.
- [ ] Inject services into ViewModels.

**THEORY 22:** Explain platform-specific code in MAUI.
**PRACTICE 22:** Implement platform-specific features.
**CHECKLIST 22:**

- [ ] Use partial classes and `#if` directives.
- [ ] Access device APIs (camera, GPS).
- [ ] Handle permissions and capabilities.

**THEORY 23:** Describe resource management in MAUI.
**PRACTICE 23:** Use images, fonts, and styles.
**CHECKLIST 23:**

- [ ] Add and reference images and fonts.
- [ ] Define and apply styles and themes.
- [ ] Handle localization and resources.

**THEORY 24:** Explain testing strategies for Blazor and MAUI.
**PRACTICE 24:** Write unit and UI tests for frontend apps.
**CHECKLIST 24:**

- [ ] Test Blazor components with bUnit.
- [ ] Test MAUI views with UI automation.
- [ ] Mock services and navigation.

**THEORY 25:** Describe accessibility in Blazor and MAUI.
**PRACTICE 25:** Implement accessible UI features.
**CHECKLIST 25:**

- [ ] Set accessibility properties (labels, roles).
- [ ] Test with screen readers and accessibility tools.
- [ ] Follow accessibility best practices.

---

**Next Steps:**
Continue atomic breakdown with advanced topics:

- Advanced Blazor (interop, performance, SSR, hybrid)
- Advanced MAUI (custom controls, graphics, platform integration)
- Unified patterns (shared code, design systems, cross-platform testing)

Let me know when to continue!

<div style="text-align: center">⁂</div>

[^1]: https://en.wikipedia.org/wiki/Paris

[^2]: https://en.wikipedia.org/wiki/List_of_capitals_of_France

[^3]: https://home.adelphi.edu/~ca19535/page 4.html

[^4]: https://www.coe.int/en/web/interculturalcities/paris

[^5]: https://www.linkedin.com/posts/sanand0_me-what-is-the-capital-of-france-qwen3-activity-7324655268640829444-Qm1Q

[^6]: https://www.britannica.com/place/Paris

[^7]: https://www.britannica.com/place/France

[^8]: https://www.tn-physio.at/faq/what-is-the-capital-of-france%3F

[^9]: https://multimedia.europarl.europa.eu/en/video/infoclip-european-union-capitals-paris-france_I199003

