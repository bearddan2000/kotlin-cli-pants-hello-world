jvm_artifact(
    name='kotlin-stdlib',
    group='org.jetbrains.kotlin',
    artifact='kotlin-stdlib',
    version='1.6.21',
)
jvm_artifact(
    name='kotlin-reflect',
    group='org.jetbrains.kotlin',
    artifact='kotlin-reflect',
    version='1.6.21',
)
jvm_artifact(
    name='kotlin-script-runtime',
    group='org.jetbrains.kotlin',
    artifact='kotlin-script-runtime',
    version='1.6.21',
)

kotlin_sources(
    name="kotlinsources",
    sources=[
        'kotlin/example/Main.kt',
    ]
)

deploy_jar(
    name="bin",
    main="example.MainKt",
    dependencies=[
        ":kotlinsources",  # refers to the `kotlin_sources` target above which has the default name
    ],
)