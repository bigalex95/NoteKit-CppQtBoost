# NoteKit-CppQtBoost

A cross-platform Notes Manager desktop app using C++ (domain logic), Qt Widgets (UI), and Boost (data serialization). Built for agile, project-based learning and demonstration of modern C++ integrations.

## Features

- Create, edit, delete notes via an intuitive Qt GUI
- Store notes in JSON or XML format with Boost.PropertyTree or Boost.Serialization
- Persistent storage: save and reload notes on app launch
- CRUD operations with robust error handling and UI feedback

## Tech Stack

- C++17 or later
- Qt Widgets (tested with Qt 6+)
- Boost (PropertyTree/Serialization/FileSystem)
- CMake (Build System, cross-platform support)

## Getting Started

1. Clone repo:  
   `git clone https://github.com/bigalex95/NoteKit-CppQtBoost.git`
2. Configure Boost and Qt on your platform (see [Boost install guide])[1]
3. Build using CMake/Qt Creator
4. Run:  
   `./NoteKit` (binary location depends on platform/settings)

## Development

- All code separated: `/src`, `/ui`, `/tests`
- Contributions: Please fork, make a feature branch, submit a PR.
- Issues tracked in GitHub Project Board with tasks mapped to agile sprints.

## License

MIT (or your preferred license)

## Resources

- [Qt Project Creation Guide][2]
- [Boost and Qt integration][3]
- [Boost with Qt Creator FAQ][1]

---

[1](https://forum.qt.io/topic/141732/how-to-install-boost-library-how-to-add-library-to-project)
[2](https://doc.qt.io/qtcreator/creator-project-creating.html)
[3](https://meetingcpp.com/index.php/br/items/building-applications-with-qt-and-boost.html)
[4](https://stackoverflow.com/questions/62359347/boost-with-qt-creator)
[5](https://developex.com/blog/how-to-make-your-c-qt-project-build-10x-faster-with-4-optimizations/)
[6](https://github.com/mloskot/qt-creator-plugin-boostbuild)
[7](https://stackoverflow.com/questions/6873936/how-to-change-a-projects-name-in-qtcreator)
[8](https://www.kdab.com/github-actions-for-cpp-and-qt/)
[9](https://stackoverflow.com/questions/18562603/how-to-configure-qt-creator-to-use-boost-in-windows)
[10](https://www.qtcentre.org/threads/33472-How-can-I-rename-the-filename-amp-projectname-in-Project)
[11](https://github.com/DarkSector/qt-project)
[12](https://www.w3computing.com/articles/exploring-cpp-standard-libraries-boost-qt/)
[13](https://forum.qt.io/topic/11245/solved-copying-renaming-a-project)
[14](https://www.qtcentre.org/threads/48135-Boost-use-it-with-Qt)
[15](https://doc.qt.io/qtinstallerframework/qtinstallerframework-openreadme-example.html)
[16](https://doc.qt.io/qtcreator/creator-project-opening.html)
[17](https://stackoverflow.com/questions/13480765/boost-with-qt-creator-and-linux/19061761)
[18](https://doc.qt.io/qtcreator/creator-how-to-use-project-wizards.html)
[19](https://www.reddit.com/r/embedded/comments/1c2781b/repos_with_professional_embedded_cc_code_education/)
[20](https://www.kdab.com/using-visual-studio-code-for-writing-qt-applications/)
