# 01 print hello world 
**shian jisjo kp{sda};'dadfa;
0x1234568795122\ 'fill':;

// var decimal = parseInt(response.getContentText(), 16);
  let result = JSON.parse(response.getContentText()).result;
  let decimal = parseInt(result, 16);
  if (isNaN(decimal)) {
    return 0;
  }
  return decimal;
}
