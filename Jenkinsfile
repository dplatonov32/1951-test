    def lib = library identifier: 'folder@fork-branch', retriever: modernSCM(
                                                                [$class: 'GitSCMSource',
                                                                 remote: 'git@github.com:Pldi23/1951-test.git',
                                                                 credentialsId: 'sshpldi23'])
    greet(lib.pkg.Clazz.whereAmI())
// if (env.CHANGE_FORK == null) {
//   def lib = library identifier: 'global@snapshot', retriever: legacySCM(scm)
//   greet(lib.pkg.Clazz.whereAmI())
// } else {
//   unstable 'Library changes may only be tested using origin branches by contributors with write access'
// }
