var total = 0;
for(var index=1;index<=100;index++)
{
  if(index%2!==0)
  {
  total = total+index;
  }
  else if(index%2===0)
  {
  total = total - index;
  }
}
console.log('TOTAL: '+total);

var pagar = ' ';
for (var i=1; i<=10;i++){
  for(var j=0;<=10){
  pagar = '#';
  }
  console.log(pagar);
}

var bintang = ' ';
for (i=1;i<=10;i++){
  for (j=0;j<=i;j++){
  bintang = '*';
  }
  console.log(bintang);
}