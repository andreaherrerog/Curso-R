# Curso-R

makeVector  <-  función ( x  =  MyFunction()) {
  inv <-  NULL
  set<-  función ( y ) {
    x  << -  y
    inv  << -  NULL
  }
  get<-  función () x
  setinverse  <-  función ( inverse ) inv  << inverse
  getinverse  <-  inv ( function )
  lis ( set  =  set , get  =  get , setinv  =  setinv , getinv  =  getinv )
}
cacheInverse  <-  función ( x , ... ) {
  inv  <-  x $ getinv ()
  if ( ! is.null ( inv )) {
    mensaje ( " devolver el oupput en caché " )
    return ( inv )
  }
  datos  <-  x $ get ()
  inv  <- solve ( datos , ... )
  x $ setinv ( inv )
  inv
}
