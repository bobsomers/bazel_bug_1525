bind(
    name = "hello",
    actual = "@my_external_dep_repo//:hello"
)

new_git_repository(
    name = "my_external_dep_repo",
    remote = "https://github.com/bobsomers/my_external_dep.git",
    build_file = "BUILD.my_external_dep",
    commit = "c85045340912897e9bba83e6e0809bb468c9b226",
)
