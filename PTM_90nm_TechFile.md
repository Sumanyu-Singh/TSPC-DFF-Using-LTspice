`````

* Predictive Technology Model Beta Version
* 90nm NMOS SPICE Parametersv (normal one)
*

.model NMOS NMOS
+Level = 49

+Lint = 1.5e-08 Tox = 2.5e-09 
+Vth0 = 0.2607 Rdsw = 180 

+lmin=1.0e-7 lmax=1.0e-7 wmin=1.0e-7 wmax=1.0e-4
+Tref=27.0   version =3.1
+Xj= 4.0000000E-08       Nch= 9.7000000E+17 
+lln= 1.0000000          lwn= 1.0000000              wln= 0.00
+wwn= 0.00               ll= 0.00
+lw= 0.00                lwl= 0.00                   wint= 0.00
+wl= 0.00                ww= 0.00                    wwl= 0.00
+Mobmod=  1              binunit= 2                  xl= 0.00
+xw= 0.00                binflag=  0
+Dwg= 0.00               Dwb= 0.00 

+ACM= 0                  ldif=0.00                   hdif=0.00
+rsh= 7                  rd= 0                       rs= 0
+rsc= 0                  rdc= 0

+K1= 0.3950000           K2= 1.0000000E-02           K3= 0.00 
+Dvt0= 1.0000000         Dvt1= 0.4000000             Dvt2= 0.1500000 
+Dvt0w= 0.00             Dvt1w= 0.00                 Dvt2w= 0.00 
+Nlx= 4.8000000E-08      W0= 0.00                    K3b= 0.00 
+Ngate= 5.0000000E+20 

+Vsat= 1.1000000E+05     Ua= -6.0000000E-10          Ub= 8.0000000E-19 
+Uc= -2.9999999E-11       
+Prwb= 0.00              Prwg= 0.00                  Wr= 1.0000000 
+U0= 1.7999999E-02       A0= 1.1000000               Keta= 4.0000000E-02 
+A1= 0.00                A2= 1.0000000               Ags= -1.0000000E-02
+B0= 0.00                B1= 0.00 

+Voff= -2.9999999E-02    NFactor= 1.5000000          Cit= 0.00 
+Cdsc= 0.00              Cdscb= 0.00                 Cdscd= 0.00 
+Eta0= 0.1500000         Etab= 0.00                  Dsub= 0.6000000 

+Pclm= 0.1000000         Pdiblc1= 1.2000000E-02      Pdiblc2= 7.5000000E-03
+Pdiblcb= -1.3500000E-02 Drout= 2.0000000            Pscbe1= 8.6600000E+08
+Pscbe2= 1.0000000E-20   Pvag= -0.2800000            Delta= 1.0000000E-02
+Alpha0= 0.00            Beta0= 30.0000000 

+kt1= -0.3700000         kt2= -4.0000000E-02         At= 5.5000000E+04 
+Ute= -1.4800000         Ua1= 9.5829000E-10          Ub1= -3.3473000E-19
+Uc1= 0.00               Kt1l= 4.0000000E-09         Prt= 0.00 

+Cj= 0.0015             Mj= 0.72                    Pb= 1.25 
+Cjsw= 2E-10            Mjsw= 0.37                  Php= 0.773
+Cjgate= 2E-14           Cta= 0                      Ctp= 0
+Pta= 0                  Ptp= 0                      JS=1.50E-08
+JSW=2.50E-13            N=1.0                       Xti=3.0
+Cgdo=3.493E-10          Cgso=3.493E-10              Cgbo=0.0E+00
+Capmod= 2               NQSMOD= 0                   Elm= 5
+Xpart= 1                cgsl= 0.582E-10             cgdl= 0.582E-10
+ckappa= 0.28            cf= 1.177e-10               clc= 1.0000000E-07
+cle= 0.6000000          Dlc= 2E-08                  Dwc= 0

*
* Predictive Technology Model Beta Version
* 90nm PMOS SPICE Parametersv (normal one)
*

.model PMOS PMOS
+Level = 49

+Lint = 1.5e-08 Tox = 2.5e-09 
+Vth0 = -0.303 Rdsw = 300 

+lmin=1.0e-7 lmax=1.0e-7 wmin=1.0e-7 wmax=1.0e-4
+Tref=27.0   version =3.1
+Xj= 4.0000000E-08             Nch= 1.0400000E+18 
+lln= 1.0000000                lwn= 0.00                          wln= 0.00
+wwn= 1.0000000                ll= 0.00                           lw= 0.00
+lwl= 0.00                     wint= 0.00                         wl= 0.00
+ww= 0.00                      wwl= 0.00                          Mobmod=  1
+binunit= 2                    xl= 0.00                           xw= 0.00
+binflag=  0                   Dwg= 0.00                          Dwb= 0.00

+ACM= 0                        ldif=0.00                          hdif=0.00
+rsh= 7                        rd= 0                              rs= 0
+rsc= 0                        rdc= 0

+K1= 0.3910000                 K2= 1.0000000E-02                  K3= 0.00 
+Dvt0= 2.6700001               Dvt1= 0.5300000                    Dvt2= 5.0000000E-02 
+Dvt0w= 0.00                   Dvt1w= 0.00                        Dvt2w= 0.00 
+Nlx= 7.5000000E-08            W0= 0.00                           K3b= 0.00 
+Ngate= 5.0000000E+20 

+Vsat= 1.0500000E+05           Ua= -5.0000000E-10                 Ub= 1.5000000E-18
+Uc= -2.9999999E-11  
+Prwb= 0.00                    Prwg= 0.00                         Wr= 1.0000000 
+U0= 5.5000000E-03             A0= 2.0000000                      Keta= 4.0000000E-02
+A1= 0.00                      A2= 0.9900000                      Ags= -0.1000000 
+B0= 0.00                      B1= 0.00 

+Voff= -7.0000000E-02          NFactor= 1.5000000                 Cit= 0.00 
+Cdsc= 0.00                    Cdscb= 0.00                        Cdscd= 0.00
+Eta0= 0.2500000               Etab= 0.00                         Dsub= 0.8000000 

+Pclm= 0.1000000               Pdiblc1= 1.2000000E-02             Pdiblc2= 7.5000000E-03 
+Pdiblcb= -1.3500000E-02       Drout= 0.9000000                   Pscbe1= 8.6600000E+08 
+Pscbe2= 1.0000000E-20         Pvag= -0.2800000                   Delta= 1.0100000E-02 
+Alpha0= 0.00                  Beta0= 30.0000000 

+kt1= -0.3400000               kt2= -5.2700000E-02                At= 0.00 
+Ute= -1.2300000               Ua1= -8.6300000E-10                Ub1= 2.0000001E-18 
+Uc1= 0.00                     Kt1l= 4.0000000E-09                Prt= 0.00 

+Cj= 0.0015                    Mj= 0.7175511                      Pb= 1.24859
+Cjsw= 2E-10                   Mjsw= 0.3706993                    Php= 0.7731149
+Cjgate= 2E-14                 Cta= 9.290391E-04                  Ctp= 7.456211E-04
+Pta= 1.527748E-03             Ptp= 1.56325E-03                   JS=2.50E-08
+JSW=4.00E-13                  N=1.0                              Xti=3.0
+Cgdo=3.49E-10                 Cgso=3.49E-10                      Cgbo=0.0E+00       
+Capmod= 2                     NQSMOD= 0                          Elm= 5            
+Xpart= 1                      cgsl= 0.582E-10                    cgdl= 0.582E-10
+ckappa= 0.28                  cf= 1.177e-10                      clc= 5.4750000E-08 
+cle= 6.4600000                Dlc= 2E-08                         Dwc= 0

`````
