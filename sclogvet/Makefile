SHELL := /bin/bash

PROGRAM_NAME := sclogvet

.PHONY: bin
bin: $(PROGRAM_NAME)
$(PROGRAM_NAME): *.go go.mod go.sum
	@go build

.PHONY: install
install:
	@go install
