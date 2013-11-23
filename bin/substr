#!/bin/bash
function substr(){
	if [[ $# -lt 1 ]] ; then
		echo "usage: substr STRING [[start] [length]] " 
		return 1
	fi
	string=$1
	start=${2:-0}
	length=${3:-${#string}}
	echo ${string: ${start} :${length}}
	return 0
}

function strlen(){
	if [[ $# -lt 1 ]] ; then
		echo "usage: strlen STRING "
		return 1
	fi
	string=$1
	echo ${#string}
	return 0
}

function strtolower(){
	if [[ $# -lt 1 ]] ; then
		echo "usage: strtolower STRING "
		return 1
	fi
	string=$1
	result=$(echo "${string}" | tr [A-Z] [a-z])
	echo $result
	return 0
}
function strtoupper(){
	if [[ $# -lt 1 ]] ; then
		echo "usage: strtoupper STRING "
		return 1
	fi
	string=$1
	result=$(echo "${string}" | tr [a-z] [A-Z])
	echo $result
	return 0

}
function strrev(){
	:
}
function strpad(){
	:
}
function strpos(){
	:
}
function strstr(){
	:
}
#------------------------------------
#    MAIN
#------------------------------------

SCRIPT=$(basename $0 )
STRING=$1
shift

$SCRIPT "$STRING" $@
