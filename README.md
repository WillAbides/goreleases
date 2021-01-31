# goreleases

This is a data repository that keeps an updated list of all go releases in 
[releases.json](https://raw.githubusercontent.com/WillAbides/goreleases/main/releases.json). The format is the same that 
you will find at https://golang.org/dl/?mode=json&include=all. The main difference is this version contains all past 
prereleases where golang.org filters them out.

This repo also filters out an errant `go1` release that golang.org presents and has file sizes for some older files that
are missing sizes on golang.org.

This repo is updated by a workflow that runs hourly. When a new version of go is released, this repo should be updated 
within the hour.
