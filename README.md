#Создаем табличку в Routes к примеру wl_routes
#Создаем Routing Rule /routing rule add dst-address-list=WL_SERVICES action=lookup table=wl_routes
#И дефолтный маршрут в ноли для таблички wl_routes через интерфейс ПРОВАЙДЕРА (pppoe-out1 к примеру)
##Далее это всё в Sheduler и раз в недельку пусть дергает.
