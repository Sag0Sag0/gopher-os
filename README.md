# gopheros
[![Build Status](https://travis-ci.org/achilleasa/gopher-os.svg?branch=master)](https://travis-ci.org/achilleasa/gopher-os)
[![codecov](https://codecov.io/gh/achilleasa/gopher-os/branch/master/graph/badge.svg)](https://codecov.io/gh/achilleasa/gopher-os)
[![Go Report Card](https://goreportcard.com/badge/github.com/achilleasa/gopher-os)](https://goreportcard.com/report/github.com/achilleasa/gopher-os)

Let's write an experimental OS in Go!

## Building
To build the OS, clone the repo, cd to it, install qemu-system-x86_64 and vagrant and enter

        vagrant up
        make iso
        qemu-system-x86_64 ./build/kernel-x86_64.iso
