<?php

print " Digite seu número de dias:";
$days = (int) fgets (STDIN);

print "Digite seu número de horas:";
$hrs = (int) fgets (STIDN);

print "Digite seu número de minutos:";
$min= (int) fgtes (STDIN);

print "Digite seu número de segundos";
$seg = (int) fgtes (STDIN);

$dias= $days*86400;
$horas= $hrs*3600;
$minutos= $min*60;

$refinal= $dias+$horas+$minutos+$seg;

print " O total será $refinal segundos";
