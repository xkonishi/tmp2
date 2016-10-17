# TortoiseGit設定

## ユーザ設定

    [http]
        proxy = http://panda.canon-mj.co.jp:9125
    [user]
        name = xkonishi
        email = konishi.cnb@gmail.com
    [gui]
        recentrepo = D:/Git/OOXML

## ローカルリポジトリ設定

    [core]
        repositoryformatversion = 0
        filemode = false
        bare = false
        logallrefupdates = true
        symlinks = false
        ignorecase = true
        hideDotFiles = dotGitOnly
    [remote "origin"]
        url = https://github.com/xkonishi/OOXML
        fetch = +refs/heads/*:refs/remotes/origin/*
    [branch "master"]
        remote = origin
        merge = refs/heads/master
    [gui]
        wmstate = normal
        geometry = 837x499+75+75 188 225


