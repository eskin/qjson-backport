# QJson backport

This is a backport of QJson from Qt5.2.1 to Qt4.8.

It is based on the initial backport from https://github.com/5in4/qjson-backport

Just add all *.cpp and *.h files to your project and add includepath. Not need to build as separate external library.

You can use standart Qt5 include syntax, like:

    #include <QJsonDocument>
    #include <QJsonObject>
    #include <QJsonArray>


# License

The license is the same, obviously, as for the library in Qt itself, LGPL 2.1. All sources include details.
