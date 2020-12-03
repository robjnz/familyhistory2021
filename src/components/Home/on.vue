<template>
  <div class="m-4 mt-10 p-4 w-auto rounded-lg">
<!--
    <h2 class="text-xl text-blue-100">
      <span style="font-size: 1em;">
        <i class="far fa-calendar-alt"></i>
      </span>
 Saturday 31 October 2020
    </h2>
    -->
    <p class="text-red-500 text-2xl">
      <span class="text-blue-100" style="font-size: 1em;">
        <i class="fas fa-virus"></i>
      </span>
      <span class="text-blue-100" style="font-size: 1em;">
        <i class="fas fa-hands-wash"></i>
        <i class="fas fa-people-arrows"></i>
      </span>
    </p>
<!--
     <h1 class="text-orange-400 text-2xl">
        <span class="text-blue-100" style="font-size: 1em;">
      <i class="fas fa-thumbs-up"></i>
      </span>
       
          Today's top pick of places to visit in London is:</h1>
  
-->
    <br />

    <div class="grid sm:flex">
      <alexandra /><!--alexandra palace-->
      <apsley /><!--Apsley House-->
      <british /><!--British Museum-->
      </div>

    <div class="grid sm:flex">
      <warrooms /><!--churchils War rooms-->
      <war /><!--Imperial War Museum-->
      <kenpalace /><!--Kensington Palace-->
      </div>

    <div class="grid sm:flex">
      <kew /><!--Kew Gardens -->
      <zoo /><!--london zoo-->
      <tussauds /><!--madame tussauds-->
      </div>

    <div class="grid sm:flex">
      <shreksadventure /><!--shreksadventure-->
      <dungeon /><!--The London Dungeon-->
      <tower /><!--Tower Of London-->
    </div>
<!--calendar 
     <div class="flex-grow">
      <calendar />
    </div>
calendar end-->
    <div class="grid sm:flex">
      <book />
    </div>
  </div>
</template>

<script>
import antioch from "@/components/Visit/antioch";
import bexley from "@/components/Visit/bexley";
import chingford from "@/components/Visit/chingford";
import danson from "@/components/Visit/danson";
import docklands from "@/components/Visit/docklands";
import eastbury from "@/components/Visit/eastbury";
import elizabeth from "@/components/Visit/elizabeth";
import eltham from "@/components/Visit/eltham";
import epping from "@/components/Visit/epping";
import fairlop from "@/components/Visit/fairlop";
import greenwich from "@/components/Visit/greenwich";
import geffrye from "@/components/Visit/geffrye";
import hackney from "@/components/Visit/hackney";
import hall from "@/components/Visit/hall";
import havering from "@/components/Visit/havering";
import horniman from "@/components/Visit/horniman";
import hospital from "@/components/Visit/hospital";
import house from "@/components/Visit/house";
import jack from "@/components/Visit/jack";
import lee from "@/components/Visit/lee";
import mayesbrook from "@/components/Visit/mayesbrook";
import mudchute from "@/components/Visit/mudchute";
import newham from "@/components/Visit/newham";
import queen from "@/components/Visit/queen";
import ragged from "@/components/Visit/ragged";
import rainham from "@/components/Visit/rainham";
import ranger from "@/components/Visit/ranger";
import red from "@/components/Visit/red";
import severndroog from "@/components/Visit/severndroog";
import sutton from "@/components/Visit/sutton";
import thames from "@/components/Visit/thames";
import tower from "@/components/Visit/tower";
import trinity from "@/components/Visit/trinity";
import upminster from "@/components/Visit/upminster";
import valence from "@/components/Visit/valence";
import valentines from "@/components/Visit/valentines";
import victoria from "@/components/Visit/victoria";
import viktor from "@/components/Visit/viktor";
import wanstead from "@/components/Visit/wanstead";
import william from "@/components/Visit/william";
import barking from "@/components/Theatres/barking";
import greenwichT from "@/components/Theatres/greenwichT";
import hackneyT from "@/components/Theatres/hackneyT";
import hoxton from "@/components/Theatres/hoxton";
import ilford from "@/components/Theatres/ilford";
import hornchurch from "@/components/Theatres/hornchurch";
import stratford from "@/components/Theatres/stratford";
import two from "@/components/Theatres/two";
import wilton from "@/components/Theatres/wilton";
import yard from "@/components/Theatres/yard";
import date from "@/components/Home/date";
import atik from "@/components/Nightclubs/atik";
import faces from "@/components/Nightclubs/faces";
import xoyo from "@/components/Nightclubs/xoyo";
import barkingF from "@/components/Football/barkingF";
import barkingside from "@/components/Football/barkingside";
import charlton from "@/components/Football/charlton";
import charltonwomen from "@/components/Football/charltonwomen";
import dagred from "@/components/Football/dagred";
import erithtown from "@/components/Football/erithtown";
import forest from "@/components/Football/forest";
import greenwichF from "@/components/Football/greenwichF";
import hornchurchF from "@/components/Football/hornchurchF";
import ilfordF from "@/components/Football/ilfordF";
import orient from "@/components/Football/orient";
import orientwomen from "@/components/Football/orientwomen";
import may from "@/components/Football/may";
import newbury from "@/components/Football/newbury";
import phoenix from "@/components/Football/phoenix";
import redbridge from "@/components/Football/redbridge";
import romford from "@/components/Football/romford";
import walthamstow from "@/components/Football/walthamstow";
import west from "@/components/Football/west";
import westwomen from "@/components/Football/westwomen";
import barkingR from "@/components/Rugby/barkingR";
import bethune from "@/components/Visit/bethune";
import crystalV from "@/components/Visit/crystalV";
import totteridge from "@/components/Visit/totteridge";
import wandsworthcommon from "@/components/Visit/wandsworthcommon";
import wimbledoncommon from "@/components/Visit/wimbledoncommon";
import batterseazoo from "@/components/Visit/batterseazoo";
import roundwood from "@/components/Visit/roundwood";
import ruislip from "@/components/Visit/ruislip";
import marblehouse from "@/components/Visit/marblehouse";
import hampstead from "@/components/Visit/hampstead";
import regentspark from "@/components/Visit/regentspark";
import regentscanal from "@/components/Visit/regentscanal";
import brockwell from "@/components/Visit/brockwell";
import zoo from "@/components/Visit/zoo";
import kew from "@/components/Visit/kew";
import morden from "@/components/Visit/morden";
import stephens from "@/components/Visit/stephens";
import kenwood from "@/components/Visit/kenwood";
import clink from "@/components/Visit/clink";
import down from "@/components/Visit/down";
import towerbridge from "@/components/Visit/towerbridge";
import airforce from "@/components/Visit/airforce";
import army from "@/components/Visit/army";
import national from "@/components/Visit/national";
import dickens from "@/components/Visit/dickens";
import tate from "@/components/Visit/tate";
import britain from "@/components/Visit/britain";
import kenpalace from "@/components/Visit/kenpalace";
import design from "@/components/Visit/design";
import warrooms from "@/components/Visit/warrooms";
import war from "@/components/Visit/war";
import tussauds from "@/components/Visit/tussauds";
import eye from "@/components/Visit/eye";
import shreksadventure from "@/components/Visit/shreksadventure";
import dungeon from "@/components/Visit/dungeon";
import apsley from "@/components/Visit/apsley";
import british from "@/components/Visit/british";
import alexandra from "@/components/Visit/alexandra";


import book from "@/components/amazon/book";
import calendar from "@/components/Home/calendar";
import today from "@/components/Home/today";


export default {
  components: {
    antioch,
    bexley,
    chingford,
    danson,
    docklands,
    eastbury,
    elizabeth,
    eltham,
    epping,
    fairlop,
    greenwich,
    geffrye,
    hackney,
    hall,
    havering,
    horniman,
    hospital,
    house,
    jack,
    lee,
    mayesbrook,
    mudchute,
    newham,
    queen,
    ragged,
    rainham,
    ranger,
    red,
    severndroog,
    sutton,
    thames,
    tower,
    trinity,
    upminster,
    valence,
    valentines,
    victoria,
    viktor,
    wanstead,
    william,
    barking,
    greenwichT,
    hackneyT,
    hornchurch,
    hoxton,
    ilford,
    stratford,
    two,
    wilton,
    yard,
    atik,
    faces,
    xoyo,
    barkingF,
    barkingside,
    charlton,
    charltonwomen,
    dagred,
    erithtown,
    forest,
    greenwichF,
    hornchurchF,
    ilfordF,
    orient,
    orientwomen,
    may,
    newbury,
    phoenix,
    redbridge,
    romford,
    walthamstow,
    west,
    westwomen,
    barkingR,
    bethune,
    crystalV,
    totteridge,
    wandsworthcommon,
    wimbledoncommon,
    batterseazoo,
    roundwood,
    ruislip,
    marblehouse,
    hampstead,
    regentspark,
    regentscanal,
    brockwell,
    zoo,
    kew,
    morden,
    stephens,
    kenwood,
    clink,
    down,
    towerbridge,
    airforce,
    army,
    national,
    dickens,
    tate,
    britain,
    kenpalace,
    design,
    warrooms,
    war,
    tussauds,
    eye,
    shreksadventure,
    dungeon,
    apsley,
    british,
    alexandra,

    book,
    calendar,
    today
  },
};
</script>
