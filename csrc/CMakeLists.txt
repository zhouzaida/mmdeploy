# Copyright (c) OpenMMLab. All rights reserved.

add_subdirectory(backend_ops)

if (MMDEPLOY_BUILD_SDK)
    add_subdirectory(core)
    add_subdirectory(archive)
    add_subdirectory(device)
    add_subdirectory(graph)
    add_subdirectory(model)
    add_subdirectory(preprocess)
    add_subdirectory(net)
    add_subdirectory(codebase)
    add_subdirectory(apis/c)
endif ()
