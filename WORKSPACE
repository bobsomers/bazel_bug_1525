bind(
    name = "hello",
    actual = "@my_external_dep_repo//:hello"
)

new_git_repository(
    name = "my_external_dep_repo",
    remote = "https://github.com/bobsomers/my_external_dep.git",
    build_file = "BUILD.my_external_dep",
    commit = "8155e474a426904c4d2912eeaa5e385338fd8940",
)
