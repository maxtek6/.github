# Maxtek Consulting

![Maxtek Consulting](https://github.com/maxtek6/.github/blob/main/profile/logo.jpeg)

Maxtek is a US-based consulting firm, originally created by Max( Guerrero) and (John Pa)tek.

## Notable Work

+ [wxWidgets](https://github.com/wxWidgets/wxWidgets) - We recently made a significant [contribution](https://github.com/wxWidgets/wxWidgets/pull/25425) to this open source project, adding support for the `StartRequest` function in the Chromium implementation of the `wxWebView` interface. This change allows developers to make direct HTTP requests from the browser to their backend code, with full access to request headers, POST data, and other information that was not available in the previous version, which only allowed static file loading. This change provides the foundation for our project [wxReactView](https://github.com/maxtek6/wxReactView).

+ [wxReactView](https://github.com/maxtek6/wxReactView) - This project is intended to provide a very similar purpose to Electron, allowing developers to create desktop applications using web bases technologies, namely ReactJS. It provides solutions for building and packaging both the C++ and JavaScript code, as well as sane interfaces to handle communication between these two components.

+ [Lariat.app](https://github.com/lariat-app) - We have been working with a client to meet their app development needs. Although this project is proprietary, it is based on wxReactView, and any changes to this project are made in the open source repository, in the interest of both the client and the community.

+ [hyperpage](hhttps://github.com/maxtek6/hyperpage) - Unsatisfied with existing solutions for bundling web content, we created a framework for reading and writing archives with the purpose of storing and serving static web content. This is one of several projects that benefits from SQLite, providing a single file with high performance read and write operations.

## Maxtek Philosophy

The Maxtek "philosophy" is just a pompous and self-important way to describe how we approach solving problems. It consists of three core principles:

+ Modularity - Most of our repositories are small to medium projects that are self-contained, such that they can be built and tested separately. These serve as building blocks for our larger projects. By using this approach, we are able to isolate problems and enable our larger projects to focus on the high level problems they are solving. This isolated approach also applies to dependency management, where we use CMake's `FetchContent` or Go's `go.mod` feature to simplify the process of integrating external projects. There is a reasonable expectation that any project downloaded using `git clone` should build without manually cloning or downloading another project, and any exception is clearly documented.

+ Compatibility - We try to make our solutions available to as many platforms as possible. Each C/C++ project has a `CMakeLists.txt` with the intention of working on any machine capable of satisfying its dependencies, which we try to limit. In the case of any platform specific code, we try to either document the inconsistencies, or abstract them away to limit their impact on other developers. This also includes license compatibility, as each project is licensed under MIT or another permissive license, giving developers the ability to include our projects in both open source and commercial projects.

+ Flexibility - We make extensive use of documentation to explain exactly what problem we are solving, and thorough testing to verify the correctness of each solution, but we try to make our work generalized and abstract, such that it can be applied to any use case that might encounter such a problem. We focus on providing interfaces and APIs, while providing minimal input as to how or where they must be used. This appears in many forms, but our interfaces often include inheritance, callback functions, and other patterns that give users a high degree of control.

## Current Members

[John](https://github.com/johnpatek) - John is a software engineer with a background in cybersecurity and cloud computing. He specializes in helping clients with 
backend development. He is an expert in C++, C, and Go.

[Max](https://github.com/a6guerre) - Max is an embedded systems engineer. With experience in aerospace and telecommunications, Max is well equipped to work with clients on embedded and low-level projects. He is well versed in embedded C and Linux kernel development.

[Colin](https://github.com/cstap14) - Colin is an undergraduate student at Liberty University, Majoring in Information Technology and Minoring in Graphic Design. His background consists of development in C++ and Java, as well as server management, primarily through Linux.