# Swift MVP + Dependency Injection Architecture

**[MVP](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93presenter)** (Model-View-Presenter) is a derivation of the model–view–controller architectural pattern, primarily used for building user interfaces. In MVP, the presenter embodies the "middle-man" functionality, consolidating all presentation logic.

In the tech world, where launching swiftly is as vital as scalability, choosing the right architecture is crucial. That's where MVP+DI comes in as a game-changer. While MVP (Model-View-Presenter) carves a distinct space for user interface, data, and logic, ensuring clarity and flexibility, DI (Dependency Injection) amplifies this by offering dynamic dependency management.

The brilliance of MVP+DI lies in its innate simplicity merged with scalability. For startups and small projects aiming for MVP (Minimum Viable Product) releases, this combination is optimal. It allows a project to start on a lean foundation but is inherently structured to accommodate growth and evolution.

In essence, if you're envisioning a project that's compact at the outset but has grand ambitions, MVP+DI is the architectural duo you've been seeking.

[![Swift Version](https://img.shields.io/badge/Swift-2.2--4.x-F16D39.svg?style=flat)](https://developer.apple.com/swift)

## Tutorials 📚

Deep dive into the structure and benefits of this architecture with these articles:
- [MVP + Dependency Injection: The Perfect Match for Scalable iOS Apps](https://medium.com/@mihail_salari/mvp-dependency-injection-the-perfect-match-for-scalable-ios-apps-51360219a28a)
- [Efficient Dependency Management in iOS: Introducing AppContainer for MVP+DI Architecture](https://medium.com/@mihail_salari/efficient-dependency-management-in-ios-introducing-appcontainer-for-mpv-di-architecture-fa6f691381b7)

## Setup 🛠

### Installation

1. **Add template to your** [Rambafile](https://github.com/rambler-digital-solutions/Generamba/wiki/Rambafile-Structure):
```yaml
templates:
 - {name: swift-mvp-injection, git: 'https://github.com/mihailsalari/swift-mvp-injection.git'}
```

2. **Install the template**:
```bash
generamba template install
```

### Usage

Generate your desired module with the following command:
```bash
generamba gen [MODULE_NAME] [TEMPLATE_NAME]
```

**Example**:

To create a Splash module:
```bash
generamba gen Splash swift-mvp-injection
```

This will generate the `Splash` module in both your project and tests target.

## Contribute 🤝

We encourage everyone to contribute and make improvements. Feel free to submit a pull request or provide feedback!

## Questions ❓

For general inquiries, consider asking on [Stack Overflow](http://stackoverflow.com/). The author regularly monitors the MVP tag there for prompt responses. Alternatively, reach out at:

- 📧 [info@mihailsalari.com](mailto:info@mihailsalari.com)
