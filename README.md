# 2627_4ia_java_receputi
//Quaderno digitale degli appunti di informatica 26/27



public simulaMath(){  
}

public double potenza (double a, int b){
  double ris = 1;
  int c = b;
  if (c<0){
    c = -c;
  }
  for (int i = 0; i<c; i++){
    ris = ris * a;
  }
  if (b<0){
    ris = 1 / ris;
  }
  return ris;
}






