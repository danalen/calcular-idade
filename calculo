<?php 
// data de nascimento
$data = '1990-10-16';

// separando yyyy, mm, ddd
list($ano, $mes, $dia) = explode('-', $data);

// data atual
$hoje = mktime(0, 0, 0, date('m'), date('d'), date('Y'));
// Descobre a unix timestamp da data de nascimento do fulano
$nascimento = mktime( 0, 0, 0, $mes, $dia, $ano);

// cálculo
$idade = floor((((($hoje - $nascimento) / 60) / 60) / 24) / 365.25);
echo "Idade: $idade Anos";
?>
