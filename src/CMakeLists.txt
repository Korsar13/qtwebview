# Copyright (C) 2022 The Qt Company Ltd.
# SPDX-License-Identifier: LicenseRef-Qt-Commercial OR GPL-3.0-only WITH Qt-GPL-exception-1.0

add_subdirectory(webview)
add_subdirectory(quick)
add_subdirectory(plugins)
if(ANDROID)
    add_subdirectory(jar)
endif()
