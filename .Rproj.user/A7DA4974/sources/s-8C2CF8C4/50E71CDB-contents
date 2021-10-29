###################c SU25 comm tech ###################
library(tidyverse)

ui <-  htmlTemplate(
  filename = "www/index.html",
  selectTech = checkboxGroupInput("SU25app", "SU25 Application:",
                                  c("New asset types configuration (DER, EV, Batteries)" = "a1",
                                    "Predictive maintenance for critical assets, DER forecasting" = "a2",
                                    "Emerging technologies based asset analytics – IoT, Drone, LiDAR, image analytics, Digital twin" = "a3",
                                    "Develop IOT based Asset Analytics Solution" = "a4",
                                    "Drone based Asset inspection PoC" = "a5",
                                    "Talk to your Asset initiative PoC" = "a6",
                                    "Dynamic Line Rating PoC" = "a7",
                                    "Advanced Load Forecasting Solution" = "a8",
                                    "Active distribution network control PoC" = "a9",
                                    "Extend digital work process to contractors" = "a10",
                                    "Enhance interfaces to manage and monitor contractors and suppliers" = "a11",
                                    "Work from anywhere" = "a12",
                                    "IoT Integration, drones based inspections" = "a13",
                                    "Digital work permits and approvals" = "a14",
                                    "Develop Smart Meter Operations Centre (SMOC)" = "a15",
                                    "Smart Meter penetration" = "a16",
                                    "Integration with Electric Vehicle & Solar Panels" = "a17",
                                    "Demand Response initiative PoC" = "a18",
                                    "Distributed Generation" = "a19",
                                    "Distributed Storage" = "a20",
                                    "Electric Vehicle" = "a21",
                                    "Transmission" = "a22",
                                    "Flexible demand" = "a23",
                                    "DER aggregation and VPP platforms RI: DER aggregation and VPP monitoring platform PoC" = "a24",
                                    "Capacity services" = "a25",
                                    "Peak Management" = "a26",
                                    "Load balancing services" = "a27",
                                    "EV services RI: Vehicle to Grid PoC" = "a28",
                                    "RE monitoring and control systems implementation" = "a29",
                                    "Grid scale ESS infrastructure implementation PoC" = "a30",
                                    "ESS hotspot analysis on Distribution Network" = "a31",
                                    "ESS connections monitoring and control framework and skill development" = "a32",
                                    "ESS monitoring and control systems implementation (DERMS)" = "a33",
                                    "EV infrastructure installation and integration PoC" = "a34",
                                    "EV monitoring and control systems implementation (DERMS)" = "a35",
                                    "EV connections. Monitoring and control ecosystem and skill development" = "a36",
                                    "P2P trading platform PoC" = "a37",
                                    "Implement NTL PoC" = "a38"
                                  ))
)

SU25 <- eventReactive(input$btnSU25,{

  a1 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a2 <- data.frame(Tech = c('5G'))
  a3 <- data.frame(Tech = c('5G'))
  a4 <- data.frame(Tech = c('5G'))
  a5 <- data.frame(Tech = c('Fiber','WiFi','4G','Pri. LTE','5G'))
  a6 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh' ,'4G','Pri. LTE','UHF','5G','SATCOM'))
  a7 <- data.frame(Tech = c('Fiber','WiFi','4G','Pri. LTE','5G'))
  a8 <- data.frame(Tech = c('Fiber','WiFi','4G','Pri. LTE','5G'))
  a9 <- data.frame(Tech = c('Fiber','WiFi','4G','Pri. LTE','5G'))

  a10 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G','SATCOM'))
  a11 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G','SATCOM'))
  a12 <- data.frame(Tech = c('5G'))
  a13 <- data.frame(Tech = c('Fiber','WiFi','4G','Pri. LTE','5G'))
  a14 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G','SATCOM'))
  a15 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','4G','Pri. LTE','5G'))
  a16 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G','SATCOM'))
  a17 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a18 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','5G'))

  a19 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a20 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a21 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a22 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','5G'))
  a23 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a24 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a25 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))

  a26 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a27 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a28 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a29 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a30 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a31 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a32 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a33 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a34 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a35 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))

  a36 <- data.frame(Tech = c('NBPLC','Fiber','WiFi','RF-Mesh','4G','Pri. LTE','UHF','5G'))
  a37 <- data.frame(Tech = c('5G'))
  a38 <- data.frame(Tech = c('5G'))



  combineTechNT<- input$SU25app

  t<-data.frame(Tech = c())
  t1<-data.frame(Tech = c())
  t2<-data.frame(Tech = c())
  t3<-data.frame(Tech = c())
  t4<-data.frame(Tech = c())
  t5<-data.frame(Tech = c())
  t6<-data.frame(Tech = c())
  t7<-data.frame(Tech = c())
  t8<-data.frame(Tech = c())
  t9<-data.frame(Tech = c())
  t10<-data.frame(Tech = c())
  t11<-data.frame(Tech = c())
  t12<-data.frame(Tech = c())
  t13<-data.frame(Tech = c())
  t14<-data.frame(Tech = c())
  t15<-data.frame(Tech = c())
  t16<-data.frame(Tech = c())
  t17<-data.frame(Tech = c())
  t18<-data.frame(Tech = c())
  t19<-data.frame(Tech = c())
  t20<-data.frame(Tech = c())
  t21<-data.frame(Tech = c())
  t22<-data.frame(Tech = c())
  t23<-data.frame(Tech = c())
  t24<-data.frame(Tech = c())
  t25<-data.frame(Tech = c())
  t26<-data.frame(Tech = c())
  t27<-data.frame(Tech = c())
  t28<-data.frame(Tech = c())
  t29<-data.frame(Tech = c())
  t30<-data.frame(Tech = c())
  t31<-data.frame(Tech = c())
  t32<-data.frame(Tech = c())
  t33<-data.frame(Tech = c())
  t34<-data.frame(Tech = c())
  t35<-data.frame(Tech = c())
  t36<-data.frame(Tech = c())
  t37<-data.frame(Tech = c())
  t38<-data.frame(Tech = c())



  for(i in 1:length(combineTechNT)){

    if(combineTechNT[i] == "a1"){

      t1<-a1
    }

    if(combineTechNT[i] == "a2"){

      t2<-a2
    }

    if(combineTechNT[i] == "a3"){

      t3<-a3
    }

    if(combineTechNT[i] == "a4"){

      t4<-a4
    }

    if(combineTechNT[i] == "a5"){

      t5<-a5
    }

    if(combineTechNT[i] == "a6"){

      t6<-a6
    }

    if(combineTechNT[i] == "a7"){

      t7<-a7
    }

    if(combineTechNT[i] == "a8"){

      t8<-a8
    }

    if(combineTechNT[i] == "a9"){

      t9<-a9
    }

    if(combineTechNT[i] == "a10"){

      t10<-a10
    }

    if(combineTechNT[i] == "a11"){

      t11<-a11
    }

    if(combineTechNT[i] == "a12"){

      t12<-a12
    }

    if(combineTechNT[i] == "a13"){

      t13<-a13
    }

    if(combineTechNT[i] == "a14"){

      t14<-a14
    }

    if(combineTechNT[i] == "a15"){

      t15<-a15
    }

    if(combineTechNT[i] == "a16"){

      t16<-a16
    }

    if(combineTechNT[i] == "a17"){

      t17<-a17
    }

    if(combineTechNT[i] == "a18"){

      t18<-a18
    }

    if(combineTechNT[i] == "a19"){

      t19<-a19
    }

    if(combineTechNT[i] == "a20"){

      t20<-a20
    }

    if(combineTechNT[i] == "a21"){

      t21<-a21
    }

    if(combineTechNT[i] == "a22"){

      t22<-a22
    }

    if(combineTechNT[i] == "a23"){

      t23<-a23
    }

    if(combineTechNT[i] == "a24"){

      t24<-a24
    }

    if(combineTechNT[i] == "a25"){

      t25<-a25
    }

    if(combineTechNT[i] == "a26"){

      t26<-a26
    }

    if(combineTechNT[i] == "a27"){

      t27<-a27
    }

    if(combineTechNT[i] == "a28"){

      t28<-a28
    }

    if(combineTechNT[i] == "a29"){

      t29<-a29
    }

    if(combineTechNT[i] == "a30"){

      t30<-a30
    }

    if(combineTechNT[i] == "a31"){

      t31<-a31
    }

    if(combineTechNT[i] == "a32"){

      t32<-a32
    }

    if(combineTechNT[i] == "a33"){

      t33<-a33
    }

    if(combineTechNT[i] == "a34"){

      t34<-a34
    }

    if(combineTechNT[i] == "a35"){

      t35<-a35
    }

    if(combineTechNT[i] == "a36"){

      t36<-a36
    }

    if(combineTechNT[i] == "a37"){

      t37<-a37
    }

    if(combineTechNT[i] == "a38"){

      t38<-a38
    }



  }


  notem <- c(t1,t2,t3,t4,t5,t6,t7,t8,t9,t10,
             t11,t12,t13,t14,t15,t16,t17,t18,t19,t20,
             t21,t22,t23,t24,t25,t26,t27,t28,t29,t30,
             t31,t32,t33,t34,t35,t36,t37,t38)

  if(length(notem)>1){

    for(n in 2:length(notem)) {

      combine <- notem[1]
      combine <- merge(combine,notem[n])

    }
  } else {
    combine <- data.frame(notem[1])
  }

  combine

})

observeEvent(input$btnSU25,{
  output$tabledata3 <- renderPrint({
    outSU25<- SU25()
    print(outSU25)
    #out
  })
})
