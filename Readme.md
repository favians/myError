

Editor: https://stackedit.io/app#

## Error Golang:

1. We would use gopath, with go module inside. VS code would error and did'nt track ur Code.
> *You are neither in a module nor in your GOPATH*

    Solution: https://www.gitmemory.com/issue/microsoft/vscode-go/3086/595981057

2. Error when starting golang (Using Gopath).

> unexpected fault address 0x7fcfb6dea000 fatal error: fault [signal
> SIGBUS: bus error code=0x2 addr=0x7fcfb6dea000 pc=0x40293e]

    Solution: Change golang folder to root ~/go


## Error NodeJS:

1. Error when nodeJS cant see watcher for changed code.
> *Nodemon Error: System limit for number of file watchers reached

    Solution: echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p

## WSL Error
1. Docker get error Docker Desktop failed to start
	> Docker get error Docker Desktop failed to start

`[https://github.com/docker/for-win/issues/4730](https://github.com/docker/for-win/issues/4730)` 

