COMPILE_DEPS = CORE_DEPS + KRYO + CLI + [
    "//core/store/serializers:onos-core-serializers",
    "//core/store/primitives:onos-core-primitives",
]

osgi_jar_with_tests(
    deps = COMPILE_DEPS,
)

onos_app(
    category = "Traffic Engineering",
    description = "One-Ping-Only sample application",
    title = "One-Ping-Only sample application",
    url = "http://onosproject.org",
)
