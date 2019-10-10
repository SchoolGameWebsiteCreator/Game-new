# Binding of Isaac
The Original

movie {
// flash 8, total frames: 41, frame rate: 30 fps, 800x600 px

  movieClip 338  {
  }

  movieClip 339 b501 {
  }

  movieClip 342  {
  }

  movieClip 344  {
  }

  movieClip 345  {
  }

  movieClip 420  {
  }

  movieClip 421  {
  }

  movieClip 444  {
  }

  movieClip 445 b98 {
  }

  movieClip 460  {
  }

  movieClip 461 b497 {
  }

  movieClip 464  {
  }

  movieClip 465 b222 {
  }

  movieClip 467  {
  }

  movieClip 468  {
  }

  movieClip 471  {
  }

  movieClip 486 b499 {

    frame 1 {
      stop();
    }
  }

  movieClip 488  {
  }

  movieClip 489 b502 {
  }

  movieClip 524  {
  }

  movieClip 531 b500 {

    frame 1 {
      stop();
    }

    frame 18 {
      done = true;
    }
  }

  movieClip 534  {
  }

  movieClip 550  {
  }

  movieClip 551  {
  }

  movieClip 552 b96 {

    frame 1 {
      stop();
    }
  }

  movieClip 553 soundz {
  }

  movieClip 556 p0 {

    frame 19 {
      done = true;
    }
  }

  movieClip 558 necksegment2 {

    frame 1 {
      _visible = false;
    }
  }

  movieClip 563  {

    frame 4 {
      stop();
    }
  }

  movieClip 567  {
  }

  movieClip 569  {
  }
  
  // unknown tag 88 length 65

  movieClip 578  {

    frame 4 {
      stop();
    }
  }

  movieClip 579  {
  }

  movieClip 607  {

    frame 1 {
      stop();
    }
  }

  movieClip 688  {

    frame 1 {
      stop();
    }
  }

  movieClip 704  {
  }

  movieClip 750  {

    frame 1 {
      stop();
    }
  }

  movieClip 753  {
  }

  movieClip 761  {
  }

  movieClip 762  {

    frame 8 {
      stop();
    }
  }

  movieClip 764  {
  }

  movieClip 766  {
  }

  movieClip 768  {
  }

  movieClip 776  {
  }

  movieClip 780  {
  }

  movieClip 782  {
  }

  movieClip 785  {
  }

  movieClip 787  {
  }

  movieClip 795  {
  }

  movieClip 814  {		//Isaac's Will Picture

    frame 1 {
      gotoAndStop(random(_totalframes) + 1);
    }
  }

  button 817 {

    on (release, keyPress '<Space>') {
      _root.a.unpause = true;
    }
  }

  button 820 {

    on (release, keyPress '<Escape>') {
      gotoAndStop(6);
    }
  }

  button 823 {

    on (rollOver) {
      _root.showoff = _currentframe;
    }
  }

  movieClip 1019  {
  }

  button 1023 {

    on (release, keyPress '<Enter>') {
      gotoAndStop(5);
    }
  }

  movieClip 1030  {
  }

  movieClip 1038  {

    frame 1 {
      gotoAndStop(_root.characterID + 1);
    }
  }

  movieClip 1135  {
  }

  movieClip 1146  {

    frame 1 {
      gotoAndStop(random(_totalframes) + 1);
    }
  }

  button 1149 {

    on (release) {
      _root.levz = undefined;
      _root.a.moveon();
      _root.door = undefined;
      _root.gotoAndStop('menu');
    }
  }

  button 1152 {

    on (release, keyPress '<Space>') {
      _root.a.moveon();
      _root.levz = undefined;
      _root.door = undefined;
      _root.a.newstart(true);
      _root.gotoAndStop('reset');
    }
  }

  movieClip 1251  {

    frame 1 {
      gotoAndStop(_root.unlll);
    }
  }

  movieClip 1252  {

    frame 1 {
      stop();
      gogo = true;
    }

    frame 87 {
      nogo = false;
    }
  }

  button 1257 {

    on (release) {
      gotoAndStop(8);
    }
  }

  button 1260 {

    on (release, keyPress '<Escape>') {
      if (_root._currentframe == 2) {
        gotoAndStop(2);
      } else {
        gotoAndStop(1);
        _root.men.men.pos = -1;
        _root.men.men.fire = 30;
      }
    }
  }

  button 1264 {

    on (release) {
      _root.doit(this);
      _root.showit();
    }
  }

  button 1268 {

    on (release) {
      _root.doit(this);
      _root.showit();
    }
  }

  movieClip 1269  {
  }

  button 1274 {

    on (release) {
      _root.qua('HIGH');
    }
  }

  movieClip 1275  {
  }

  button 1280 {

    on (release) {
      _root.qua('MEDIUM');
    }
  }

  movieClip 1281  {
  }

  button 1286 {

    on (release) {
      _root.qua('AUTO');
    }
  }

  movieClip 1287  {
  }

  button 1292 {

    on (release) {
      _root.qua('LOW');
    }
  }

  movieClip 1293  {
  }

  movieClip 1295  {
  }
  
  // unknown tag 88 length 78

  button 1299 {

    on (release) {
      _root.reser(_currentframe);
    }
  }

  movieClip 1307  {
  }

  button 1311 {

    on (release) {
      _root.wiq(2);
    }
  }

  movieClip 1312  {
  }

  button 1313 {

    on (release) {
      _root.wiq(true);
    }
  }

  movieClip 1314  {
  }

  button 1318 {

    on (release) {
      _root.wiq(false);
    }
  }

  movieClip 1319  {
  }

  button 1322 {

    on (release) {
      _root.a.unpause = true;
    }
  }

  button 1323 {

    on (release) {
      _root.levz = undefined;
      _root.a.moveon();
      _root.door = undefined;
      _root.gotoAndStop('menu');
    }
  }

  button 1328 {

    on (release, keyPress '<Enter>') {
      _root.levz = undefined;
      _root.a.moveon();
      _root.door = undefined;
      _root.gotoAndStop('menu');
    }
  }

  button 1331 {

    on (release, keyPress '<Escape>') {
      gotoAndStop(2);
    }
  }

  button 1334 {

    on (release) {
      so = SharedObject.getLocal('so', '/');
      so.clear();
      so.flush();
      var myAppPath = mdm.Application.path;
      mdm.FileSystem.deleteFile(myAppPath + 'serial.txt');
      _root.soz();
      _parent.prevFrame();
    }
  }

  button 1335 {

    on (release, keyPress '<Escape>') {
      _parent.prevFrame();
    }
  }

  movieClip 1336  {
  }

  button 1338 {

    on (release, keyPress '<Escape>') {
      gotoAndStop(5);
    }
  }

  button 1342 {

    on (release) {
      _parent.chal(this);
    }
  }

  movieClip 1345  {
  }

  movieClip 1348  {
  }

  movieClip 1351  {
  }

  movieClip 1354  {
  }

  movieClip 1357  {
  }

  movieClip 1360  {
  }

  movieClip 1363  {
  }

  movieClip 1366  {
  }

  movieClip 1369  {
  }

  movieClip 1372  {
  }

  button 1373 {

    on (release, keyPress '<Escape>') {
      if (_root._currentframe == 2) {
        gotoAndStop(5);
      } else {
        gotoAndStop(1);
        _root.men.men.pos = -1;
        _root.men.men.fire = 30;
      }
    }
  }

  movieClip 1374  {

    frame 1 {
      function itit() {
        f2 = true;
        f3 = true;
        i = 0;
        while (i < 20) {
          trg = this['i' + i];
          f1 = _root.collectionScreen[i];
          if (f1 > 0) {
            trg.gotoAndStop(f1);
          } else {
            if (_root.colit > 0 && f2) {
              f2 = false;
              trg.gotoAndStop(_root.colit);
            } else {
              if (_root.spacebarItem == 11 && f3) {
                f3 = false;
                if (_root.pillItem >= 7) {
                  trg.gotoAndStop(61);
                } else {
                  trg.gotoAndStop(43);
                }
              } else {
                trg._visible = false;
              }
            }
          }
          ++i;
        }
      }

      stop();
    }

    frame 2 {
      itit();
    }

    frame 3 {
      itit();
      _root.unl.gogo = true;
    }

    frame 5 {
      _root.qshow();
      itit();
      _root.showit();
    }

    frame 6 {
      itit();
    }

    frame 8 {
      _root.qshow();
      itit();
      _root.showit();
    }

    frame 9 {
      function chal(trg) {
        _root.tex = men.cha.characterID;
        _root.characterID = 0;
        _root.men.men.cha.characterID = 0;
        _root.challenge = trg.e;
        _root.darky(150);
      }

      _root.lox = [0, 76, 78, 77, 79, 81, 80, 82, 83, 84, 86];
      lox = 4;
      if (_root.SecretUnlocked[4]) {
        lox = 9;
      }
      if (_root.so.data.polaroidCounter > 0) {
        lox = 11;
      }
      e = 0;
      while (e < 11) {
        trg = this['c' + e];
        trg.e = e;
        if (lox < e) {
          trg.gotoAndStop(3);
        } else {
          if (_root.SecretUnlocked[_root.lox[e]]) {
            trg.gotoAndStop(2);
          } else {
            trg.gotoAndStop(1);
          }
        }
        ++e;
      }
      _root.challenge = 0;
    }
  }

  movieClip 1376  {
  }

  movieClip 1379  {
  }

  movieClip 1381  {

    frame 9 {
      _parent.prevFrame();
    }
  }

  movieClip 1382  {

    frame 7 {
      _parent.nextFrame();
    }
  }

  movieClip 1383  {
  }

  movieClip 1384  {
  }

  movieClip 1386  {
  }

  movieClip 1389  {
  }

  movieClip 1392  {

    frame 83 {
      stop();
      _visible = false;
    }
  }

  movieClip 1393 hud {

    frame 1 {
      _visible = false;
    }
  }

  movieClip 1397  {
  }

  movieClip 1399  {
  }

  movieClip 1400 hearter {
  }

  movieClip 1402  {
  }

  movieClip 1403  {
  }

  movieClip 1405  {
  }

  movieClip 1406  {

    frame 41 {
      _parent.nextFrame();
    }
  }

  movieClip 1407 fireblock {

    frame 1 {
      stop();
      fire = true;
    }
  }

  movieClip 1408 emptyz {
  }

  movieClip 1410  {

    frame 1 {
      stop();
    }
  }

  movieClip 1411 bullet1 {
  }

  movieClip 1417  {
  }

  movieClip 1418  {
  }

  movieClip 1419  {

    frame 23 {
      stop();
    }
  }

  movieClip 1421  {
  }

  movieClip 1422  {

    frame 19 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 1423 breakblock {

    frame 1 {
      stop();
    }
  }

  movieClip 1440 bloodsplash {

    frame 17 {
      done = true;
    }
  }

  movieClip 1445  {

    frame 1 {
      gotoAndStop(random(_totalframes) + 1);
    }
  }

  movieClip 1446 bloo {

    frame 141 {
      done = true;
    }
  }

  movieClip 1448  {
  }

  movieClip 1449 batter {
  }

  movieClip 1466  {
  }

  movieClip 1467  {
  }

  movieClip 1468  {
  }

  movieClip 1469 b13 {

    frame 1 {
      stop();
    }
  }

  movieClip 1481  {
  }

  movieClip 1482  {

    frame 1 {
      stop();
    }
  }

  movieClip 1491  {
  }

  movieClip 1496  {
  }

  movieClip 1497  {

    frame 1 {
      stop();
    }
  }

  movieClip 1509  {
  }

  movieClip 1512  {
  }

  movieClip 1524  {
  }

  movieClip 1525  {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 1542  {
  }

  movieClip 1544  {

    frame 1 {
      stop();
    }
  }

  movieClip 1557  {
  }

  movieClip 1571  {
  }

  movieClip 1572  {

    frame 1 {
      stop();
    }
  }

  movieClip 1586  {
  }

  movieClip 1587  {

    frame 1 {
      stop();
    }
  }

  movieClip 1601  {
  }

  movieClip 1602  {

    frame 1 {
      stop();
    }
  }

  movieClip 1605  {
  }

  movieClip 1615  {
  }

  movieClip 1616  {

    frame 1 {
      stop();
    }
  }

  movieClip 1640  {
  }

  movieClip 1642  {
  }

  movieClip 1644  {
  }

  movieClip 1645  {

    frame 26 {
      stop();
    }
  }

  movieClip 1648  {
  }

  movieClip 1649  {
  }

  movieClip 1650  {

    frame 1 {
      stop();
    }
  }

  movieClip 1652  {
  }

  movieClip 1656  {

    frame 1 {
      stop();
    }
  }

  movieClip 1659  {

    frame 1 {
      stop();
    }
  }

  movieClip 1660  {
  }

  movieClip 1663  {

    frame 1 {
      stop();
    }
  }

  movieClip 1666  {

    frame 1 {
      stop();
    }
  }

  movieClip 1667  {
  }

  movieClip 1682  {
  }

  movieClip 1683  {
  }

  movieClip 1686  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 1689  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 1692  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 1694  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 1695  {

    frame 1 {
      gotoAndStop(_parent._parent._parent.stomps + 1);
    }
  }

  movieClip 1720  {
  }

  movieClip 1738  {
  }

  movieClip 1739 b3 {

    frame 1 {
      stop();
    }
  }

  movieClip 1789 b2 {

    frame 1 {
      stop();
    }

    frame 18 {
      done = true;
    }
  }

  movieClip 1791  {
  }

  movieClip 1792  {

    frame 192 {
      done = true;
    }
  }

  movieClip 1794  {
  }

  movieClip 1796  {
  }

  movieClip 1797  {
  }

  movieClip 1798 ball {
  }

  movieClip 1801  {
  }

  movieClip 1802 b9 {

    frame 1 {
      stop();
    }

    frame 18 {
      done = true;
    }
  }

  movieClip 1806 gibs-red {

    frame 1 {
      gotoAndStop(random(_totalframes) + 1);
    }
  }

  movieClip 1807  {
  }

  movieClip 1816 b8 {

    frame 1 {
      stop();
    }

    frame 18 {
      done = true;
    }
  }

  movieClip 1818  {
  }

  movieClip 1820  {
  }

  movieClip 1822  {
  }

  movieClip 1824  {
  }

  movieClip 1826  {
  }

  movieClip 1828  {
  }

  movieClip 1830  {
  }

  movieClip 1831  {
  }

  movieClip 1833  {
  }

  movieClip 1834  {
  }

  movieClip 1835  {

    frame 15 {
      _parent.nextFrame();
    }
  }

  movieClip 1836  {
  }

  movieClip 1838  {
  }

  movieClip 1840  {
  }

  movieClip 1842  {
  }

  movieClip 1843  {
  }

  movieClip 1844  {
  }

  movieClip 1845  {
  }

  movieClip 1846  {
  }

  movieClip 1848  {
  }

  movieClip 1850  {
  }

  movieClip 1851  {
  }

  movieClip 1852  {
  }

  movieClip 1853  {
  }

  movieClip 1854  {
  }

  movieClip 1855  {
  }

  movieClip 1856  {
  }

  movieClip 1857  {
  }

  movieClip 1858 b74 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 1862  {

    frame 1 {
      gotoAndStop(random(_totalframes) + 1);
    }
  }

  movieClip 1863 b7 {

    frame 1 {
      stop();
    }

    frame 18 {
      done = true;
    }
  }

  movieClip 1866  {
  }

  movieClip 1868  {
  }

  movieClip 1871  {
  }

  movieClip 1872  {
  }

  movieClip 1873  {
  }

  movieClip 1874 b54 {

    frame 1 {
      stop();
    }
  }

  movieClip 1879  {

    frame 1 {
      stop();
    }
  }

  movieClip 1880  {
  }

  movieClip 1881  {
  }

  movieClip 1897  {
  }

  movieClip 1898  {

    frame 35 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 1899  {
  }

  movieClip 1904  {

    frame 1 {
      stop();
    }
  }

  movieClip 1911  {
  }

  movieClip 1927  {
  }

  movieClip 1928  {

    frame 35 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 1929  {
  }

  movieClip 1932  {
  }

  movieClip 1933  {
  }

  movieClip 1935  {
  }

  movieClip 1936  {

    frame 1 {
      stop();
    }
  }

  movieClip 1937  {
  }

  movieClip 1953  {
  }

  movieClip 1954  {

    frame 35 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 1955  {
  }

  movieClip 1963  {

    frame 1 {
      if (_parent._parent._parent._parent.s != 4) {
        _visible = false;
      }
    }
  }

  movieClip 1966  {
  }

  movieClip 1967  {
  }

  movieClip 1970  {
  }

  movieClip 1971  {
  }

  movieClip 1973  {

    frame 1 {
      stop();
    }
  }

  movieClip 1989  {
  }

  movieClip 1990  {

    frame 26 {
      _root.soundy('Fetus_Land_1.wav', 100);
    }

    frame 35 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 1991  {

    frame 59 {
      _parent._parent.dones = true;
      _parent.gotoAndStop(3);
    }
  }

  movieClip 1992  {
  }

  movieClip 1993  {
  }

  movieClip 1995  {
  }

  movieClip 2017  {

    frame 20 {
      stop();
    }
  }

  movieClip 2020  {
  }

  movieClip 2024  {

    frame 22 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 2027  {
  }

  movieClip 2035  {

    frame 20 {
      stop();
    }
  }

  movieClip 2040  {

    frame 22 {
      _parent.gotoAndStop(5);
    }
  }

  movieClip 2042  {
  }

  movieClip 2065  {

    frame 20 {
      stop();
    }
  }

  movieClip 2077  {

    frame 19 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 2079  {
  }

  movieClip 2090  {
  }

  movieClip 2091  {
  }

  movieClip 2107  {
  }

  movieClip 2108  {

    frame 35 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 2109  {
  }

  movieClip 2112  {
  }

  movieClip 2114  {
  }

  movieClip 2116  {
  }

  movieClip 2119  {

    frame 1 {
      _root.a.slotReeler(this);
    }
  }

  movieClip 2123  {

    frame 1 {
      _root.a.slotReeler(this);
    }
  }

  movieClip 2126  {

    frame 1 {
      _root.a.slotReeler(this);
    }
  }

  movieClip 2128  {
  }

  movieClip 2130  {
  }

  movieClip 2132  {
  }

  movieClip 2134  {
  }

  movieClip 2135  {
  }

  movieClip 2137  {
  }

  movieClip 2139  {
  }

  movieClip 2140  {
  }

  movieClip 2141  {
  }

  movieClip 2143  {
  }

  movieClip 2144  {
  }

  movieClip 2145  {
  }

  movieClip 2147  {
  }

  movieClip 2148  {
  }

  movieClip 2150  {
  }

  movieClip 2151  {
  }

  movieClip 2152  {
  }

  movieClip 2153  {
  }

  movieClip 2154  {
  }

  movieClip 2157  {

    frame 1 {
      _root.a.slotReeler(this);
    }
  }

  movieClip 2158  {

    frame 41 {
      stop();
    }
  }

  movieClip 2164  {
  }

  movieClip 2166  {
  }

  movieClip 2168  {
  }

  movieClip 2169  {
  }

  movieClip 2171  {
  }

  movieClip 2172  {

    frame 37 {
      stop();
    }
  }

  movieClip 2176  {

    frame 1 {
      stop();
    }
  }

  movieClip 2177  {
  }

  movieClip 2180  {
  }

  movieClip 2183  {

    frame 1 {
      stop();
    }
  }

  movieClip 2184  {
  }

  movieClip 2185  {
  }

  movieClip 2186  {
  }

  movieClip 2187  {

    frame 61 {
      _parent._parent._parent.done = true;
    }
  }

  movieClip 2190  {

    frame 1 {
      stop();
    }
  }

  movieClip 2192  {
  }

  movieClip 2193  {
  }

  movieClip 2194  {
  }

  movieClip 2195  {
  }

  movieClip 2196  {
  }

  movieClip 2197  {

    frame 1 {
      stop();
    }
  }

  movieClip 2199  {
  }

  movieClip 2201  {
  }

  movieClip 2212  {

    frame 1 {
      stop();
    }
  }

  movieClip 2217  {
  }

  movieClip 2222  {
  }

  movieClip 2227  {
  }

  movieClip 2232  {
  }

  movieClip 2237  {
  }

  movieClip 2243  {
  }

  movieClip 2248  {
  }

  movieClip 2253  {

    frame 1 {
      stop();
    }
  }

  movieClip 2258  {

    frame 1 {
      stop();
    }
  }

  movieClip 2263  {

    frame 1 {
      stop();
    }
  }

  movieClip 2268  {
  }

  movieClip 2270  {
  }

  movieClip 2271  {
  }

  movieClip 2276  {
  }

  movieClip 2281  {
  }

  movieClip 2285  {
  }

  movieClip 2289  {
  }

  movieClip 2294  {
  }

  movieClip 2299  {
  }

  movieClip 2304  {
  }

  movieClip 2309  {
  }

  movieClip 2314  {
  }

  movieClip 2318  {
  }

  movieClip 2324  {
  }

  movieClip 2325  {
  }

  movieClip 2330  {
  }

  movieClip 2335  {
  }

  movieClip 2339  {
  }

  movieClip 2344  {
  }

  movieClip 2347  {
  }

  movieClip 2351  {
  }

  movieClip 2355  {

    frame 1 {
      stop();
    }
  }

  movieClip 2360  {
  }

  movieClip 2363  {
  }

  movieClip 2368  {
  }

  movieClip 2375  {
  }

  movieClip 2384  {
  }

  movieClip 2393  {

    frame 1 {
      stop();
    }
  }

  movieClip 2395  {
  }

  movieClip 2396  {
  }

  movieClip 2401  {
  }

  movieClip 2410  {

    frame 1 {
      stop();
    }

    frame 1 {
      stop();
    }
  }

  movieClip 2419  {

    frame 1 {
      stop();
    }
  }

  movieClip 2428  {
  }

  movieClip 2437  {
  }

  movieClip 2444  {
  }

  movieClip 2448  {
  }

  movieClip 2455  {
  }

  movieClip 2458  {
  }

  movieClip 2467  {
  }

  movieClip 2474  {
  }

  movieClip 2477  {
  }

  movieClip 2486  {
  }

  movieClip 2493  {
  }

  movieClip 2496  {
  }

  movieClip 2502  {
  }

  movieClip 2506  {
  }

  movieClip 2513  {
  }

  movieClip 2519  {
  }

  movieClip 2520  {
  }

  movieClip 2525  {
  }

  movieClip 2534  {
  }

  movieClip 2543  {
  }

  movieClip 2544  {

    frame 1 {
      stop();
    }
  }

  movieClip 2549  {
  }

  movieClip 2557  {

    frame 1 {
      stop();
    }
  }

  movieClip 2566  {

    frame 1 {
      stop();
    }
  }

  movieClip 2575  {

    frame 1 {
      stop();
    }
  }

  movieClip 2584  {

    frame 1 {
      stop();
    }
  }

  movieClip 2593  {

    frame 1 {
      stop();
    }
  }

  movieClip 2602  {

    frame 1 {
      stop();
    }
  }

  movieClip 2611  {

    frame 1 {
      stop();
    }
  }

  movieClip 2614  {
  }

  movieClip 2617  {
  }

  movieClip 2620  {
  }

  movieClip 2621  {

    frame 1 {
      stop();
    }

    frame 5 {
      stop();
    }
  }

  movieClip 2634  {
  }

  movieClip 2638  {

    frame 1 {
      stop();
    }
  }

  movieClip 2647  {

    frame 1 {
      stop();
    }
  }

  movieClip 2656  {

    frame 1 {
      stop();
    }
  }

  movieClip 2665  {

    frame 1 {
      stop();
    }
  }

  movieClip 2670  {
  }

  movieClip 2673  {
  }

  movieClip 2678  {
  }

  movieClip 2682  {

    frame 1 {
      stop();
    }
  }

  movieClip 2685  {
  }

  movieClip 2688  {
  }

  movieClip 2689  {
  }

  movieClip 2692  {

    frame 1 {
      stop();
    }
  }

  movieClip 2701  {

    frame 1 {
      stop();
    }
  }

  movieClip 2710  {

    frame 1 {
      stop();
    }
  }

  movieClip 2717  {
  }

  movieClip 2724  {
  }

  movieClip 2731  {
  }

  movieClip 2736  {

    frame 1 {
      stop();
    }
  }

  movieClip 2745  {

    frame 1 {
      stop();
    }
  }

  movieClip 2754  {

    frame 1 {
      stop();
    }

    frame 5 {
      stop();
    }
  }

  movieClip 2763  {

    frame 1 {
      stop();
    }
  }

  movieClip 2772  {

    frame 1 {
      stop();
    }
  }

  movieClip 2781  {

    frame 1 {
      stop();
    }
  }

  movieClip 2787  {
  }

  movieClip 2790  {
  }

  movieClip 2793  {
  }

  movieClip 2796  {
  }

  movieClip 2801  {

    frame 1 {
      stop();
    }
  }

  movieClip 2810  {

    frame 1 {
      stop();
    }
  }

  movieClip 2819  {

    frame 1 {
      stop();
    }
  }

  movieClip 2832  {

    frame 1 {
      stop();
    }
  }

  movieClip 2845  {

    frame 1 {
      stop();
    }
  }

  movieClip 2854  {

    frame 1 {
      stop();
    }
  }

  movieClip 2863  {

    frame 1 {
      stop();
    }
  }

  movieClip 2870  {
  }

  movieClip 2871  {
  }

  movieClip 2872  {
  }

  movieClip 2879  {
  }

  movieClip 2880  {
  }

  movieClip 2881  {
  }

  movieClip 2888  {
  }

  movieClip 2889  {
  }

  movieClip 2890  {
  }

  movieClip 2896  {
  }

  movieClip 2902  {

    frame 1 {
      stop();
    }
  }

  movieClip 2908  {
  }

  movieClip 2910  {
  }

  movieClip 2911  {

    frame 1 {
      stop();
    }
  }

  movieClip 2920  {

    frame 1 {
      stop();
    }
  }

  movieClip 2929  {

    frame 1 {
      stop();
    }
  }

  movieClip 2938  {

    frame 1 {
      stop();
    }
  }

  movieClip 2947  {

    frame 1 {
      stop();
    }
  }

  movieClip 2956  {

    frame 1 {
      stop();
    }
  }

  movieClip 2965  {

    frame 1 {
      stop();
    }
  }

  movieClip 2974  {

    frame 1 {
      stop();
    }

    frame 5 {
      stop();
    }
  }

  movieClip 2983  {

    frame 1 {
      stop();
    }
  }

  movieClip 2992  {

    frame 1 {
      stop();
    }
  }

  movieClip 3001  {

    frame 1 {
      stop();
    }
  }

  movieClip 3010  {

    frame 1 {
      stop();
    }
  }

  movieClip 3019  {

    frame 1 {
      stop();
    }
  }

  movieClip 3020  {

    frame 1 {
      stop();
    }
  }

  movieClip 3021  {
  }

  movieClip 3026  {

    frame 1 {
      _root.a.gish(this, 2);
    }
  }

  movieClip 3030  {

    frame 1 {
      _root.a.gish(this, 2);
    }
  }

  movieClip 3037  {
  }

  movieClip 3043  {
  }

  movieClip 3046  {
  }

  movieClip 3051  {
  }

  movieClip 3054  {
  }

  movieClip 3059  {
  }

  movieClip 3072  {
  }

  movieClip 3085  {
  }

  movieClip 3098  {
  }

  movieClip 3108  {

    frame 1 {
      stop();
    }
  }

  movieClip 3113  {
  }

  movieClip 3114  {

    frame 1 {
      gotoAndStop(Math.min(8, _root.a.sk));
    }
  }

  movieClip 3115  {

    frame 1 {
      stop();
    }

    frame 56 {
      _root.a.nextcha();
    }
  }

  movieClip 3119  {

    frame 1 {
      stop();
    }
  }

  movieClip 3176  {
  }

  movieClip 3189  {
  }

  movieClip 3304  {
  }

  movieClip 3305  {

    frame 20 {
      gotoAndPlay(1);
    }

    frame 21 {
      stop();
    }
  }

  movieClip 3306  {
  }

  movieClip 3318  {
  }

  movieClip 3320  {
  }

  movieClip 3321  {

    frame 49 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 3323  {
  }

  movieClip 3324  {

    frame 17 {
      stop();
    }
  }

  movieClip 3325  {
  }

  movieClip 3326 b5 {
  }

  movieClip 3328  {
  }

  movieClip 3330  {
  }

  movieClip 3332  {
  }

  movieClip 3334  {
  }

  movieClip 3336  {
  }

  movieClip 3337  {
  }

  movieClip 3339  {
  }

  movieClip 3340  {
  }

  movieClip 3342  {
  }

  movieClip 3343  {
  }

  movieClip 3345  {
  }

  movieClip 3346  {
  }

  movieClip 3349  {
  }

  movieClip 3350  {
  }

  movieClip 3351 b45 {
  }

  movieClip 3352  {
  }

  movieClip 3354  {
  }

  movieClip 3355  {
  }

  movieClip 3356  {

    frame 93 {
      _parent.gotoAndStop(6);
      _parent._parent.dones = true;
    }
  }

  movieClip 3357 b4 {

    frame 1 {
      stop();
    }
  }

  movieClip 3359  {
  }

  movieClip 3361  {
  }

  movieClip 3363  {
  }

  movieClip 3365  {
  }

  movieClip 3366  {
  }

  movieClip 3368  {
  }

  movieClip 3369  {
  }

  movieClip 3370  {
  }

  movieClip 3372  {
  }

  movieClip 3373  {
  }

  movieClip 3374  {

    frame 9 {
      now = true;
    }
  }

  movieClip 3376  {
  }

  movieClip 3378  {
  }

  movieClip 3380  {
  }

  movieClip 3381  {

    frame 16 {
      now = true;
    }
  }

  movieClip 3382  {

    frame 16 {
      now = true;
    }
  }

  movieClip 3383  {

    frame 16 {
      now = true;
    }
  }

  movieClip 3384  {

    frame 5 {
      now = true;
    }

    frame 8 {
      if (_root.a.ball.length < 15) {
        now = true;
      }
    }
  }

  movieClip 3385  {

    frame 18 {
      now = true;
    }
  }

  movieClip 3386 b36 {
  }

  movieClip 3388  {
  }

  movieClip 3390  {
  }

  movieClip 3392  {
  }

  movieClip 3394  {
  }

  movieClip 3396  {
  }

  movieClip 3398  {
  }

  movieClip 3400  {
  }

  movieClip 3402  {
  }

  movieClip 3404  {
  }

  movieClip 3405  {
  }

  movieClip 3406  {
  }

  movieClip 3407  {
  }

  movieClip 3408  {
  }

  movieClip 3409  {
  }

  movieClip 3410  {
  }

  movieClip 3411  {
  }

  movieClip 3412 b20 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 3415  {
  }

  movieClip 3416  {
  }

  movieClip 3417 b17 {

    frame 1 {
      stop();
    }
  }

  movieClip 3431  {
  }

  movieClip 3432  {
  }

  movieClip 3433 b11 {

    frame 1 {
      stop();
    }
  }

  movieClip 3435  {
  }

  movieClip 3436  {
  }

  movieClip 3438  {
  }

  movieClip 3440  {
  }

  movieClip 3441  {

    frame 1 {
      stop();
    }
  }

  movieClip 3442  {
  }

  movieClip 3443 b91 {

    frame 1 {
      stop();
    }
  }

  movieClip 3445  {
  }

  movieClip 3446  {
  }

  movieClip 3447  {
  }

  movieClip 3448 b92 {

    frame 1 {
      stop();
    }
  }

  movieClip 3451  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3452  {
  }

  movieClip 3453  {
  }

  movieClip 3456  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3459  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3462  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3463 b97 {
  }

  movieClip 3465  {
  }

  movieClip 3466  {
  }

  movieClip 3467  {
  }

  movieClip 3468  {
  }

  movieClip 3469  {
  }

  movieClip 3470  {
  }

  movieClip 3471  {
  }

  movieClip 3472  {
  }

  movieClip 3473  {
  }

  movieClip 3474 b99 {
  }

  movieClip 3477  {
  }

  movieClip 3479  {
  }

  movieClip 3481  {
  }

  movieClip 3483  {

    frame 1 {
      stop();
      if (_root.godRoomFloor && _root.lev != _root.bossRoom) {
        gotoAndStop(2);
      }
    }
  }

  movieClip 3485  {
  }

  movieClip 3487  {
  }

  movieClip 3488  {
  }

  movieClip 3494  {
  }

  movieClip 3496  {
  }

  movieClip 3498  {
  }

  movieClip 3500  {
  }

  movieClip 3502  {
  }

  movieClip 3504  {
  }

  movieClip 3506  {
  }

  movieClip 3507  {
  }

  movieClip 3509  {
  }

  movieClip 3510  {
  }

  movieClip 3511  {
  }

  movieClip 3513  {
  }

  movieClip 3515  {
  }

  movieClip 3517  {
  }

  movieClip 3519  {
  }

  movieClip 3521  {
  }

  movieClip 3522  {
  }

  movieClip 3523  {
  }

  movieClip 3525  {
  }

  movieClip 3526  {
  }

  movieClip 3529  {
  }

  movieClip 3531  {
  }

  movieClip 3535  {
  }

  movieClip 3536  {
  }

  movieClip 3537 b84 {
  }

  movieClip 3539  {
  }

  movieClip 3542  {

    frame 1 {
      if (_root.SecretUnlocked[45]) {
        gotoAndStop(2);
      } else {
        gotoAndStop(1);
      }
    }
  }

  movieClip 3543  {
  }

  movieClip 3545  {
  }

  movieClip 3546  {
  }

  movieClip 3547  {
  }

  movieClip 3548  {
  }

  movieClip 3549  {
  }

  movieClip 3550  {

    frame 14 {
      stop();
    }
  }

  movieClip 3551 b78 {
  }

  movieClip 3565  {
  }

  movieClip 3578  {
  }

  movieClip 3579  {
  }

  movieClip 3588  {

    frame 1 {
      stop();
    }
  }

  movieClip 3589  {
  }

  movieClip 3591  {
  }

  movieClip 3593  {
  }

  movieClip 3595  {
  }

  movieClip 3599  {
  }

  movieClip 3600  {
  }

  movieClip 3602  {
  }

  movieClip 3604  {
  }

  movieClip 3605  {
  }

  movieClip 3606 b52 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 3608  {
  }

  movieClip 3610  {
  }

  movieClip 3612  {
  }

  movieClip 3614  {
  }

  movieClip 3616  {
  }

  movieClip 3618  {
  }

  movieClip 3619  {
  }

  movieClip 3620  {
  }

  movieClip 3621  {
  }

  movieClip 3623  {
  }

  movieClip 3624  {
  }

  movieClip 3626  {
  }

  movieClip 3627  {

    frame 27 {
      _parent.nextFrame();
    }
  }

  movieClip 3628  {
  }

  movieClip 3629  {
  }

  movieClip 3630  {
  }

  movieClip 3632  {
  }

  movieClip 3633  {
  }

  movieClip 3634 b63 {
  }

  movieClip 3637  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3640  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3643  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3644  {
  }

  movieClip 3647  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3650  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3651  {
  }

  movieClip 3654  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3657  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3658  {
  }

  movieClip 3659  {
  }

  movieClip 3662  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3663  {
  }

  movieClip 3664  {
  }

  movieClip 3665  {
  }

  movieClip 3666 b43 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 3669  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3672  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3676  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3677  {

    frame 1 {
      function onEnterFrame() {
        gotoAndStop(_root.slugeye);
      }

      gotoAndStop(_root.slugeye);
    }
  }

  movieClip 3679  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3680  {
  }

  movieClip 3681  {
  }

  movieClip 3684  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3687  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3688  {
  }

  movieClip 3689  {
  }

  movieClip 3692  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3695  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3696  {
  }

  movieClip 3697  {
  }

  movieClip 3698  {
  }

  movieClip 3700  {
  }

  movieClip 3701  {
  }

  movieClip 3702  {

    frame 33 {
      _parent.nextFrame();
    }
  }

  movieClip 3703  {
  }

  movieClip 3704  {
  }

  movieClip 3705  {
  }

  movieClip 3706 b68 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 3708  {
  }

  movieClip 3710  {
  }

  movieClip 3712  {
  }

  movieClip 3715  {
  }

  movieClip 3716  {
  }

  movieClip 3717  {
  }

  movieClip 3718  {
  }

  movieClip 3721  {
  }

  movieClip 3723  {
  }

  movieClip 3724 b51 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 3726  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3729  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3732  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3735  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3736  {
  }

  movieClip 3737  {
  }

  movieClip 3738  {
  }

  movieClip 3741  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3744  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3745  {
  }

  movieClip 3746  {
  }

  movieClip 3747  {
  }

  movieClip 3750  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3751  {
  }

  movieClip 3754  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3755  {
  }

  movieClip 3756 b69 {

    frame 1 {
      stop();
    }
  }

  movieClip 3759  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3760  {
  }

  movieClip 3761  {
  }

  movieClip 3764  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3765  {
  }

  movieClip 3766  {
  }

  movieClip 3769  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 3770  {
  }

  movieClip 3771 b71 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 3773  {
  }

  movieClip 3776  {
  }

  movieClip 3777  {

    frame 1 {
      stop();
    }
  }

  movieClip 3778  {
  }

  movieClip 3779  {

    frame 9 {
      doit = true;
    }
  }

  movieClip 3780  {

    frame 8 {
      doit = true;
    }

    frame 10 {
      doit = true;
    }

    frame 13 {
      doit = true;
    }

    frame 15 {
      doit = true;
    }

    frame 17 {
      doit = true;
    }

    frame 19 {
      doit = true;
    }

    frame 21 {
      doit = true;
    }

    frame 23 {
      doit = true;
    }
  }

  movieClip 3781  {
  }

  movieClip 3782 b60 {

    frame 1 {
      stop();
    }
  }

  movieClip 3784  {
  }

  movieClip 3786  {
  }

  movieClip 3788  {
  }

  movieClip 3790  {
  }

  movieClip 3792  {
  }

  movieClip 3794  {
  }

  movieClip 3796  {
  }

  movieClip 3797  {
  }

  movieClip 3798  {
  }

  movieClip 3799  {
  }

  movieClip 3800  {
  }

  movieClip 3801  {
  }

  movieClip 3803  {
  }

  movieClip 3804  {
  }

  movieClip 3805 b59 {

    frame 1 {
      stop();
    }
  }

  movieClip 3808  {
  }

  movieClip 3809  {
  }

  movieClip 3812  {
  }

  movieClip 3813  {
  }

  movieClip 3814 b56 {

    frame 1 {
      stop();
    }
  }

  movieClip 3828  {
  }

  movieClip 3829  {
  }

  movieClip 3835  {
  }

  movieClip 3843  {
  }

  movieClip 3845  {
  }

  movieClip 3854  {

    frame 1 {
      stop();
    }
  }

  movieClip 3855  {
  }

  movieClip 3857  {
  }

  movieClip 3858  {
  }

  movieClip 3859 b53 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 3866  {
  }

  movieClip 3867  {
  }

  movieClip 3868  {
  }

  movieClip 3870  {
  }

  movieClip 3872  {
  }

  movieClip 3873  {
  }

  movieClip 3874  {
  }

  movieClip 3875 b58 {

    frame 1 {
      stop();
    }
  }

  movieClip 3878  {
  }

  movieClip 3880  {
  }

  movieClip 3881  {
  }

  movieClip 3882  {
  }

  movieClip 3883  {
  }

  movieClip 3884 b57 {

    frame 1 {
      stop();
    }
  }

  movieClip 3889  {
  }

  movieClip 3894  {
  }

  movieClip 3899  {
  }

  movieClip 3900  {
  }

  movieClip 3905  {
  }

  movieClip 3910  {
  }

  movieClip 3915  {
  }

  movieClip 3916  {
  }

  movieClip 3917  {
  }

  movieClip 3922  {
  }

  movieClip 3927  {
  }

  movieClip 3932  {
  }

  movieClip 3933  {
  }

  movieClip 3934 b55 {

    frame 1 {
      stop();
    }
  }

  movieClip 3937  {
  }

  movieClip 3938  {

    frame 26 {
      _parent.nextFrame();
    }
  }

  movieClip 3939 locktile {

    frame 1 {
      stop();
    }
  }

  movieClip 3944  {
  }

  movieClip 3945  {
  }

  movieClip 3946  {
  }

  movieClip 3947 b32 {

    frame 1 {
      stop();
    }
  }

  movieClip 3949  {
  }

  movieClip 3950  {
  }

  movieClip 3952  {
  }

  movieClip 3953  {
  }

  movieClip 3955  {
  }

  movieClip 3956  {
  }

  movieClip 3957  {
  }

  movieClip 3958 b34 {

    frame 1 {
      stop();
    }
  }

  movieClip 3961  {
  }

  movieClip 3964  {
  }

  movieClip 3967  {
  }

  movieClip 3968  {

    frame 1 {
      stop();
    }
  }

  movieClip 3969  {
  }

  movieClip 3978  {
  }

  movieClip 3979 b26 {

    frame 1 {
      stop();
    }
  }

  movieClip 3981  {
  }

  movieClip 3982  {
  }

  movieClip 3984  {
  }

  movieClip 3985  {
  }

  movieClip 3986  {
  }

  movieClip 3988  {
  }

  movieClip 3989  {
  }

  movieClip 3990 b21 {

    frame 1 {
      stop();
    }
  }

  movieClip 3995  {
  }

  movieClip 4000  {
  }

  movieClip 4001  {
  }

  movieClip 4002  {
  }

  movieClip 4003 b61 {

    frame 1 {
      stop();
    }
  }

  movieClip 4007  {
  }

  movieClip 4008  {
  }

  movieClip 4012  {
  }

  movieClip 4016  {
  }

  movieClip 4020  {
  }

  movieClip 4024  {
  }

  movieClip 4025  {
  }

  movieClip 4026  {
  }

  movieClip 4030  {
  }

  movieClip 4031  {
  }

  movieClip 4032 b15 {
  }

  movieClip 4041  {
  }

  movieClip 4042  {
  }

  movieClip 4043 b80 {

    frame 1 {
      stop();
    }
  }

  movieClip 4046  {
  }

  movieClip 4049  {
  }

  movieClip 4050  {
  }

  movieClip 4053  {
  }

  movieClip 4054  {
  }

  movieClip 4064  {
  }

  movieClip 4080  {
  }

  movieClip 4081  {
  }

  movieClip 4082 b14 {

    frame 1 {
      stop();
    }
  }

  movieClip 4086  {
  }

  movieClip 4105  {
  }

  movieClip 4115  {
  }

  movieClip 4116 b12 {

    frame 1 {
      stop();
    }
  }

  movieClip 4117  {
  }

  movieClip 4118 b18 {

    frame 1 {
      stop();
    }
  }

  movieClip 4120  {
  }

  movieClip 4122  {
  }

  movieClip 4124  {
  }

  movieClip 4125  {
  }

  movieClip 4126  {
  }

  movieClip 4127  {
  }

  movieClip 4129  {
  }

  movieClip 4131  {
  }

  movieClip 4132  {
  }

  movieClip 4134  {
  }

  movieClip 4135  {
  }

  movieClip 4136  {
  }

  movieClip 4137  {

    frame 33 {
      _parent.gotoAndStop(11);
    }
  }

  movieClip 4138  {
  }

  movieClip 4139  {
  }

  movieClip 4140  {
  }

  movieClip 4141  {
  }

  movieClip 4143  {
  }

  movieClip 4144  {
  }

  movieClip 4145  {
  }

  movieClip 4146  {
  }

  movieClip 4147 b66 {
  }

  movieClip 4149  {
  }

  movieClip 4150  {
  }

  movieClip 4152  {
  }

  movieClip 4153  {
  }

  movieClip 4154  {
  }

  movieClip 4156  {
  }

  movieClip 4157  {
  }

  movieClip 4159  {
  }

  movieClip 4160  {
  }

  movieClip 4162  {
  }

  movieClip 4163  {
  }

  movieClip 4164  {
  }

  movieClip 4165 b31 {

    frame 1 {
      stop();
    }
  }

  movieClip 4167  {
  }

  movieClip 4169  {
  }

  movieClip 4171  {
  }

  movieClip 4173  {
  }

  movieClip 4175  {
  }

  movieClip 4176  {
  }

  movieClip 4178  {
  }

  movieClip 4180  {
  }

  movieClip 4181  {
  }

  movieClip 4183  {
  }

  movieClip 4184  {
  }

  movieClip 4185  {
  }

  movieClip 4186  {
  }

  movieClip 4187  {
  }

  movieClip 4189  {
  }

  movieClip 4191  {
  }

  movieClip 4192  {
  }

  movieClip 4193 b64 {
  }

  movieClip 4199  {
  }

  movieClip 4200  {
  }

  movieClip 4213  {
  }

  movieClip 4215  {
  }

  movieClip 4220  {
  }

  movieClip 4224  {
  }

  movieClip 4227  {
  }

  movieClip 4231  {
  }

  movieClip 4235  {
  }

  movieClip 4238  {
  }

  movieClip 4242  {
  }

  movieClip 4246  {
  }

  movieClip 4247  {
  }

  movieClip 4250  {
  }

  movieClip 4253  {
  }

  movieClip 4254  {
  }

  movieClip 4257  {
  }

  movieClip 4260  {
  }

  movieClip 4261  {
  }

  movieClip 4262 b39 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 4264  {
  }

  movieClip 4278  {

    frame 1 {
      stop();
    }
  }

  movieClip 4293  {

    frame 1 {
      stop();
    }
  }

  movieClip 4308  {

    frame 1 {
      stop();
    }
  }

  movieClip 4309  {
  }

  movieClip 4310  {
  }

  movieClip 4311  {
  }

  movieClip 4312  {
  }

  movieClip 4313 b30 {
  }

  movieClip 4315 necksegment {

    frame 1 {
      _visible = false;
    }
  }

  movieClip 4328  {
  }

  movieClip 4330  {
  }

  movieClip 4331 b35 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 4334  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4337  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4340  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4343  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4346  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4349  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4350  {
  }

  movieClip 4351  {
  }

  movieClip 4352  {
  }

  movieClip 4355  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4356  {
  }

  movieClip 4359  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4360  {

    frame 37 {
      gotoAndStop(_currentframe - 2);
    }
  }

  movieClip 4363  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4364  {

    frame 27 {
      _parent.nextFrame();
    }
  }

  movieClip 4365  {
  }

  movieClip 4370  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4373  {
  }

  movieClip 4374 b65 {
  }

  movieClip 4376  {
  }

  movieClip 4377  {
  }

  movieClip 4378  {
  }

  movieClip 4379  {
  }

  movieClip 4380 b40 {

    frame 1 {
      stop();
    }
  }

  movieClip 4383  {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 4384  {
  }

  movieClip 4385 b44 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 4386  {
  }

  movieClip 4387  {
  }

  movieClip 4388 b29 {

    frame 1 {
      stop();
    }
  }

  movieClip 4390  {
  }

  movieClip 4391  {
  }

  movieClip 4393  {
  }

  movieClip 4395  {
  }

  movieClip 4397  {
  }

  movieClip 4398 b93 {

    frame 1 {
      stop();
    }
  }

  movieClip 4401  {
  }

  movieClip 4413  {
  }

  movieClip 4414  {
  }

  movieClip 4422  {
  }

  movieClip 4423 b87 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 4426  {
  }

  movieClip 4429  {
  }

  movieClip 4430  {
  }

  movieClip 4443  {
  }

  movieClip 4456  {
  }

  movieClip 4469  {
  }

  movieClip 4470  {
  }

  movieClip 4471  {
  }

  movieClip 4472  {
  }

  movieClip 4473 b88 {
  }

  movieClip 4482  {

    frame 1 {
      stop();
    }
  }

  movieClip 4483  {
  }

  movieClip 4485  {
  }

  movieClip 4486  {
  }

  movieClip 4487 b86 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 4491  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4495  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4499  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4503  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4507  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4511  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4515  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4519  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4523  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4527  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4531  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4535  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4539  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4543  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4547  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4548  {

    frame 1 {
      stop();
    }
  }

  movieClip 4552  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4556  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4558  {
  }

  movieClip 4562  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4563  {

    frame 22 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 4564  {

    frame 22 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 4565  {

    frame 22 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 4566  {
  }

  movieClip 4567  {
  }

  movieClip 4568  {
  }

  movieClip 4569  {
  }

  movieClip 4570  {
  }

  movieClip 4571  {
  }

  movieClip 4572  {
  }

  movieClip 4573  {
  }

  movieClip 4574  {
  }

  movieClip 4575  {
  }

  movieClip 4576 b28 {
  }

  movieClip 4578  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4583  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4584  {
  }

  movieClip 4585  {
  }

  movieClip 4586  {
  }

  movieClip 4590  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4595  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4596  {
  }

  movieClip 4601  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4602  {
  }

  movieClip 4603  {
  }

  movieClip 4604 b67 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 4617  {
  }

  movieClip 4618  {

    frame 1 {
      stop();
    }
  }

  movieClip 4622  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4626  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4630  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4634  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4635  {
  }

  movieClip 4639  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4640  {
  }

  movieClip 4643  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4646  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4647  {
  }

  movieClip 4651  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4660  {
  }

  movieClip 4662  {

    frame 1 {
      _root.a.gish(this, true);
    }
  }

  movieClip 4663  {
  }

  movieClip 4667  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4671  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4672  {
  }

  movieClip 4673  {

    frame 18 {
      _parent.nextFrame();
    }
  }

  movieClip 4674  {
  }

  movieClip 4675  {
  }

  movieClip 4676 b79 {
  }

  movieClip 4678  {
  }

  movieClip 4679  {
  }

  movieClip 4681  {
  }

  movieClip 4682  {
  }

  movieClip 4683  {
  }

  movieClip 4686  {
  }

  movieClip 4689  {
  }

  movieClip 4692  {
  }

  movieClip 4693 b23 {

    frame 1 {
      stop();
    }
  }

  movieClip 4695  {
  }

  movieClip 4697  {
  }

  movieClip 4698  {
  }

  movieClip 4700  {
  }

  movieClip 4701  {
  }

  movieClip 4703  {
  }

  movieClip 4705  {
  }

  movieClip 4706  {
  }

  movieClip 4707 b89 {
  }

  movieClip 4710  {
  }

  movieClip 4713  {
  }

  movieClip 4714  {
  }

  movieClip 4715  {
  }

  movieClip 4716 b25 {

    frame 1 {
      stop();
    }
  }

  movieClip 4720  {

    frame 1 {
      stop();
    }
  }

  movieClip 4722  {
  }

  movieClip 4724  {
  }

  movieClip 4734  {

    frame 50 {
      _root.soundy('death_reverse.wav');
    }

    frame 74 {
      _parent.hp += 15;
      _parent.outway = false;
    }
  }

  movieClip 4735 b24 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 4737  {
  }

  movieClip 4739  {
  }

  movieClip 4744  {
  }

  movieClip 4745  {
  }

  movieClip 4746  {
  }

  movieClip 4747 b90 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 4756  {
  }

  movieClip 4757  {
  }

  movieClip 4760  {
  }

  movieClip 4761  {

    frame 1 {
      stop();
    }
  }

  movieClip 4765  {
  }

  movieClip 4766  {
  }

  movieClip 4770  {
  }

  movieClip 4772  {
  }

  movieClip 4773  {
  }

  movieClip 4774 b16 {

    frame 1 {
      stop();
    }
  }

  movieClip 4779  {
  }

  movieClip 4785  {
  }

  movieClip 4794  {
  }

  movieClip 4795  {
  }

  movieClip 4796 b85 {

    frame 1 {
      stop();
    }
  }

  movieClip 4798  {
  }

  movieClip 4799 b94 {

    frame 1 {
      stop();
    }
  }

  movieClip 4812  {
  }

  movieClip 4825  {
  }

  movieClip 4826  {
  }

  movieClip 4830  {
  }

  movieClip 4833  {
  }

  movieClip 4834  {

    frame 1 {
      stop();
    }
  }

  movieClip 4839  {

    frame 1 {
      stop();
    }
  }

  movieClip 4840  {
  }

  movieClip 4842  {
  }

  movieClip 4843 b41 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 4845  {
  }

  movieClip 4847  {

    frame 1 {
      _visible = false;
    }
  }

  movieClip 4848  {
  }

  movieClip 4849  {

    frame 9 {
      open = true;
    }

    frame 55 {
      open = false;
    }

    frame 62 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 4850 b27 {

    frame 1 {
      stop();
    }
  }

  movieClip 4852  {
  }

  movieClip 4853  {
  }

  movieClip 4854  {
  }

  movieClip 4856  {
  }

  movieClip 4857  {
  }

  movieClip 4858  {

    frame 24 {
      _parent.nextFrame();
    }
  }

  movieClip 4860  {
  }

  movieClip 4861  {
  }

  movieClip 4862 b83 {
  }

  movieClip 4864  {
  }

  movieClip 4866  {
  }

  movieClip 4868  {
  }

  movieClip 4871  {

    frame 1 {
      _root.a.horsch(this);
    }
  }

  movieClip 4872  {
  }

  movieClip 4873  {
  }

  movieClip 4874  {
  }

  movieClip 4875  {
  }

  movieClip 4876 b82 {
  }

  movieClip 4880  {

    frame 1 {
      stop();
    }
  }

  movieClip 4881  {
  }

  movieClip 4882  {
  }

  movieClip 4883  {
  }

  movieClip 4886  {

    frame 1 {
      stop();
    }
  }

  movieClip 4887  {
  }

  movieClip 4888 b22 {

    frame 1 {
      stop();
    }
  }

  movieClip 4890  {
  }

  movieClip 4892  {
  }

  movieClip 4894  {
  }

  movieClip 4897  {
  }

  movieClip 4898  {
  }

  movieClip 4899  {
  }

  movieClip 4900  {
  }

  movieClip 4903  {
  }

  movieClip 4906  {
  }

  movieClip 4907  {
  }

  movieClip 4911  {
  }

  movieClip 4915  {
  }

  movieClip 4916  {
  }

  movieClip 4918  {
  }

  movieClip 4919  {

    frame 15 {
      _parent.nextFrame();
    }
  }

  movieClip 4920  {
  }

  movieClip 4921  {
  }

  movieClip 4922 b81 {
  }

  movieClip 4927  {
  }

  movieClip 4928 egg {

    frame 1 {
      stop();
      egg = true;
    }
  }

  movieClip 4948  {

    frame 1 {
      stop();
    }
  }

  movieClip 4956  {
  }

  movieClip 4958  {
  }

  movieClip 4959 b10 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 4961  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4964  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4965  {
  }

  movieClip 4966  {
  }

  movieClip 4969  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4972  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4973  {
  }

  movieClip 4976  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4977  {
  }

  movieClip 4980  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 4981  {
  }

  movieClip 4982  {
  }

  movieClip 4983 b101 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 4985  {
  }

  movieClip 4992  {
  }

  movieClip 4993 b46 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 4997  {
  }

  movieClip 4998  {
  }

  movieClip 4999  {
  }

  movieClip 5003  {
  }

  movieClip 5004  {
  }

  movieClip 5005  {
  }

  movieClip 5006  {
  }

  movieClip 5007 b38 {

    frame 1 {
      stop();
    }
  }

  movieClip 5010  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5011  {
  }

  movieClip 5014  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5015  {
  }

  movieClip 5018  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5021  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5024  {
  }

  movieClip 5027  {
  }

  movieClip 5028  {
  }

  movieClip 5029  {
  }

  movieClip 5032  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5035  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5038  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5041  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5042  {
  }

  movieClip 5052  {
  }

  movieClip 5053  {
  }

  movieClip 5056  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5057  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5058  {

    frame 17 {
      stop();
    }
  }

  movieClip 5059 b62 {
  }

  movieClip 5061  {
  }

  movieClip 5062  {
  }

  movieClip 5065  {
  }

  movieClip 5066  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5067  {
  }

  movieClip 5071  {
  }

  movieClip 5074  {
  }

  movieClip 5077  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5080  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5082  {
  }

  movieClip 5085  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5086  {
  }

  movieClip 5087  {
  }

  movieClip 5090  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5091  {
  }

  movieClip 5092  {
  }

  movieClip 5095  {

    frame 1 {
      _root.a.gish(this, true);
    }
  }

  movieClip 5096  {
  }

  movieClip 5097  {
  }

  movieClip 5098  {
  }

  movieClip 5099  {
  }

  movieClip 5100 b102 {
  }

  movieClip 5103  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5106  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5109  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5112  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5115  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5116  {
  }

  movieClip 5117  {
  }

  movieClip 5120  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5121  {
  }

  movieClip 5122  {
  }

  movieClip 5125  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5126  {
  }

  movieClip 5129  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5130  {
  }

  movieClip 5133  {

    frame 1 {
      _root.a.gish(this);
    }
  }

  movieClip 5134  {
  }

  movieClip 5135 b100 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 5144  {

    frame 1 {
      stop();
    }
  }

  movieClip 5145  {
  }

  movieClip 5154  {

    frame 1 {
      stop();
    }
  }

  movieClip 5155  {

    frame 7 {
      if (_root.a.altboss) {
        d.gotoAndStop(5);
      }
    }
  }

  movieClip 5156  {
  }

  movieClip 5157  {

    frame 7 {
      if (_root.a.altboss) {
        d.d.gotoAndStop(5);
      }
    }
  }

  movieClip 5158 b19 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 5163  {
  }

  movieClip 5168  {

    frame 23 {
      stop();
    }
  }

  movieClip 5169 breakblock4 {

    frame 1 {
      stop();
    }
  }

  movieClip 5178  {

    frame 1 {
      stop();
    }
  }

  movieClip 5187  {

    frame 1 {
      stop();
    }
  }

  movieClip 5188  {
  }

  movieClip 5190  {
  }

  movieClip 5191  {
  }

  movieClip 5194  {
  }

  movieClip 5195 b50 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 5200  {

    frame 1 {
      stop();
    }
  }

  movieClip 5201  {
  }

  movieClip 5203  {
  }

  movieClip 5204  {
  }

  movieClip 5205 b48 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 5211  {

    frame 1 {
      stop();
    }
  }

  movieClip 5212  {
  }

  movieClip 5224  {
  }

  movieClip 5225  {
  }

  movieClip 5226  {
  }

  movieClip 5227 b47 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 5228  {
  }

  movieClip 5231  {
  }

  movieClip 5232  {
  }

  movieClip 5235  {
  }

  movieClip 5237  {
  }

  movieClip 5238 b49 {

    frame 1 {
      stop();
      h.stop();
    }
  }

  movieClip 5239 toothhit {
  }

  movieClip 5241  {
  }

  movieClip 5245  {
  }

  movieClip 5247  {
  }

  movieClip 5248  {
  }

  movieClip 5250  {
  }

  movieClip 5254  {
  }

  movieClip 5255  {
  }

  movieClip 5268  {
  }

  movieClip 5281  {
  }

  movieClip 5282  {
  }

  movieClip 5285  {
  }

  movieClip 5286  {
  }

  movieClip 5290  {
  }

  movieClip 5291  {
  }

  movieClip 5293  {
  }

  movieClip 5294  {
  }

  movieClip 5298  {
  }

  movieClip 5299  {
  }

  movieClip 5313  {
  }

  movieClip 5314  {
  }

  movieClip 5316  {
  }

  movieClip 5329  {
  }

  movieClip 5342  {
  }

  movieClip 5343  {

    frame 1 {
      stop();
    }
  }

  movieClip 5355  {
  }

  movieClip 5368  {
  }

  movieClip 5369  {

    frame 1 {
      stop();
    }
  }

  movieClip 5376  {
  }

  movieClip 5378  {
  }

  movieClip 5391  {
  }

  movieClip 5392  {

    frame 1 {
      stop();
    }
  }

  movieClip 5394  {
  }

  movieClip 5395  {
  }

  movieClip 5398  {
  }

  movieClip 5410  {
  }

  movieClip 5411  {
  }

  movieClip 5413  {
  }

  movieClip 5414  {
  }

  movieClip 5423  {
  }

  movieClip 5424  {
  }

  movieClip 5426  {
  }

  movieClip 5428  {
  }

  movieClip 5430  {
  }

  movieClip 5433  {

    frame 1 {
      _root.a.horsch(this);
    }
  }

  movieClip 5434  {

    frame 1 {
      stop();
    }
  }

  movieClip 5437  {

    frame 1 {
      stop();
    }
  }

  movieClip 5441  {

    frame 1 {
      stop();
    }
  }

  movieClip 5443  {
  }

  movieClip 5444  {
  }

  movieClip 5448  {
  }

  movieClip 5449  {
  }

  movieClip 5451  {
  }

  movieClip 5452  {
  }

  movieClip 5454  {
  }

  movieClip 5458  {
  }

  movieClip 5459  {
  }

  movieClip 5462  {
  }

  movieClip 5474  {
  }

  movieClip 5477  {
  }

  movieClip 5489  {
  }

  movieClip 5490  {
  }

  movieClip 5499  {
  }

  movieClip 5500  {
  }

  movieClip 5501  {
  }

  movieClip 5504  {
  }

  movieClip 5506  {
  }

  movieClip 5507  {
  }

  movieClip 5509  {
  }

  movieClip 5517  {
  }

  movieClip 5518  {
  }

  movieClip 5519  {

    frame 1 {
      stop();
    }
  }

  movieClip 5520  {

    frame 1 {
      stop();
    }
  }

  movieClip 5521  {
  }

  movieClip 5524  {

    frame 1 {
      _root.a.horsch(this);
    }
  }

  movieClip 5525  {
  }

  movieClip 5536  {
  }

  movieClip 5537  {
  }

  movieClip 5539  {
  }

  movieClip 5541  {
  }

  movieClip 5543  {
  }

  movieClip 5548  {
  }

  movieClip 5552  {
  }

  movieClip 5553  {
  }

  movieClip 5554  {
  }

  movieClip 5555  {
  }

  movieClip 5556  {
  }

  movieClip 5557  {
  }

  movieClip 5558  {
  }

  movieClip 5559  {
  }

  movieClip 5560  {
  }

  movieClip 5563  {
  }

  movieClip 5565  {
  }

  movieClip 5566  {
  }

  movieClip 5567  {

    frame 42 {
      stop();
    }
  }

  movieClip 5568  {
  }

  movieClip 5569  {

    frame 42 {
      stop();
    }
  }

  movieClip 5570  {

    frame 42 {
      stop();
    }
  }

  movieClip 5571  {

    frame 42 {
      stop();
    }
  }

  movieClip 5573  {
  }

  movieClip 5574  {

    frame 42 {
      stop();
    }
  }

  movieClip 5575  {

    frame 42 {
      stop();
    }
  }

  movieClip 5577  {
  }

  movieClip 5578  {

    frame 42 {
      stop();
    }
  }

  movieClip 5579  {

    frame 42 {
      stop();
    }
  }

  movieClip 5580  {
  }

  movieClip 5584  {
  }

  movieClip 5585  {
  }

  movieClip 5586  {
  }

  movieClip 5587  {
  }

  movieClip 5588  {
  }

  movieClip 5589  {
  }

  movieClip 5590  {
  }

  movieClip 5591  {
  }

  movieClip 5592  {
  }

  movieClip 5593  {
  }

  movieClip 5596  {
  }

  movieClip 5600  {
  }

  movieClip 5601  {
  }

  movieClip 5602  {
  }

  movieClip 5603  {
  }

  movieClip 5605  {
  }

  movieClip 5607  {
  }

  movieClip 5608  {
  }

  movieClip 5610  {
  }

  movieClip 5611  {

    frame 78 {
      stop();
    }
  }

  movieClip 5613  {
  }

  movieClip 5614  {
  }

  movieClip 5615  {

    frame 78 {
      stop();
    }
  }

  movieClip 5617  {
  }

  movieClip 5618  {
  }

  movieClip 5619  {

    frame 78 {
      stop();
    }
  }

  movieClip 5621  {
  }

  movieClip 5622  {
  }

  movieClip 5623  {

    frame 78 {
      stop();
    }
  }

  movieClip 5625  {
  }

  movieClip 5626  {
  }

  movieClip 5627  {

    frame 78 {
      stop();
    }
  }

  movieClip 5629  {
  }

  movieClip 5630  {
  }

  movieClip 5631  {

    frame 78 {
      stop();
    }
  }

  movieClip 5633  {
  }

  movieClip 5634  {
  }

  movieClip 5635  {

    frame 78 {
      stop();
    }
  }

  movieClip 5636  {
  }

  movieClip 5637  {

    frame 78 {
      stop();
    }
  }

  movieClip 5638  {
  }

  movieClip 5640  {
  }

  movieClip 5641  {
  }

  movieClip 5642  {
  }

  movieClip 5647  {
  }

  movieClip 5649  {
  }

  movieClip 5654  {
  }

  movieClip 5662  {
  }

  movieClip 5670  {
  }

  movieClip 5678  {
  }

  movieClip 5689  {
  }

  movieClip 5697  {
  }

  movieClip 5705  {
  }

  movieClip 5713  {
  }

  movieClip 5714  {
  }

  movieClip 5715  {
  }

  movieClip 5716  {
  }

  movieClip 5718  {
  }

  movieClip 5719  {
  }

  movieClip 5721  {
  }

  movieClip 5722  {
  }

  movieClip 5727  {
  }

  movieClip 5730  {
  }

  movieClip 5731  {
  }

  movieClip 5736  {
  }

  movieClip 5739  {
  }

  movieClip 5741  {
  }

  movieClip 5742  {
  }

  movieClip 5743  {
  }

  movieClip 5744  {

    frame 20 {
      stop();
    }
  }

  movieClip 5745  {

    frame 20 {
      stop();
    }
  }

  movieClip 5746  {

    frame 21 {
      stop();
    }
  }

  movieClip 5747  {

    frame 20 {
      stop();
    }
  }

  movieClip 5748  {

    frame 20 {
      stop();
    }
  }

  movieClip 5749  {

    frame 20 {
      stop();
    }
  }

  movieClip 5750  {

    frame 21 {
      stop();
    }
  }

  movieClip 5751  {

    frame 20 {
      stop();
    }
  }

  movieClip 5752  {
  }

  movieClip 5753 b1 {

    frame 1 {
      stop();
    }
  }

  movieClip 5759  {
  }

  movieClip 5760  {

    frame 23 {
      stop();
    }
  }

  movieClip 5762  {
  }

  movieClip 5763  {

    frame 19 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 5764 breakblock2 {

    frame 1 {
      stop();
    }
  }

  movieClip 5770  {
  }

  movieClip 5771  {

    frame 23 {
      stop();
    }
  }

  movieClip 5772 breakblock3 {

    frame 1 {
      stop();
    }
  }

  movieClip 5773  {

    frame 1 {
      stop();
      fire = true;
    }
  }

  movieClip 5774 fireblock2 {
  }

  movieClip 5776  {
  }

  movieClip 5777  {
  }

  movieClip 5779  {
  }

  movieClip 5780  {

    frame 18 {
      stop();
    }
  }

  movieClip 5781  {
  }

  movieClip 5782 b42 {
  }

  frame 1 {
    function nooo() {
      if (!linx) {
        mdm.Application.exit();
      } else {
        fscommand('quit');
      }
    }

    function ffss1(f0) {
      if (f0 == true) {
        f0 = 1;
      }
      if (f0 <= 0) {
        f0 = 0;
      }
      return f0;
    }

    function add(v1) {
      if (v1.length > 0) {
        f1 += ',' + ffss1(v1[0]);
        z = 1;
        while (z < v1.length) {
          f1 += '\'' + ffss1(v1[z]);
          ++z;
        }
      } else {
        if (v1 == undefined or !v1 or v1 == 'false') {
          v1 = 0;
        }
        f1 += ',' + v1;
      }
    }

    function sub(f3) {
      ++f1;
      var v1 = checker2[f1];
      if (f3) {
        v1 = v1.split('\'');
        for (z in v1) {
          v1[z] *= 1;
          if (v1[z] <= 0) {
            v1[z] = 0;
          }
        }
        return v1;
      } else {
        if (v1 * 1 > 0) {
          v1 *= 1;
        }
        if (v1 == 'undefined') {
          v1 = undefined;
        }
        if (v1 == 'true') {
          v1 = true;
        }
        if (v1 == 'false') {
          v1 = false;
        }
        if (v1 == '0') {
          v1 = 0;
        }
        return v1;
      }
    }

    function aloc() {
      checker1 = new Array(200);
      e = 0;
      while (e < 200) {
        checker1[e] = checker[e];
        ++e;
      }
      for (e in SecretUnlocked) {
        if (e > 0) {
          if (SecretUnlocked[e]) {
            f1 = e * 2 + 11;
            checker1[f1] += e % 4 + 1;
            if (checker1[f1] > 9) {
              checker1[f1] -= 9;
            }
          }
        }
      }
      f1 = '';
      e = 0;
      while (e < 200) {
        f1 += checker1[e];
        ++e;
      }
      add(so.data.frog);
      add(so.data.left);
      add(so.data.frog);
      add(so.data.momKills);
      add(so.data.poopsDestroyed);
      add(so.data.bloodDonations);
      add(so.data.deathCardUses);
      add(so.data.arcadesVisited);
      add(so.data.bomb);
      add(so.data.timesDied);
      add(so.data.rocksBombed);
      add(so.data.collectionScreen);
      add(so.data.boss);
      add(so.data.levelsCompleted);
      add(so.data.mwin);
      add(so.data.rox);
      add(so.data.polaroidCounter);
      if (!linx) {
        var v1 = mdm.Application.path;
        mdm.FileSystem.saveFile(v1 + 'serial.txt', f1);
      }
    }

    function aloc2() {
      if (!linx) {
        var v3 = mdm.Application.path;
        var v2 = mdm.FileSystem.loadFile(v3 + 'serial.txt');
        checker2 = v2.split(',');
        f1 = 0;
        if (!so.data.cocks) {
          if (so.data.timesDied > 5) {
            so.data.cocks = true;
          }
          if (checker2.length > 10) {
            so.data.cocks = true;
            so.data.frog = sub();
            so.data.left = sub();
            so.data.frog = sub();
            so.data.momKills = sub();
            so.data.poopsDestroyed = sub();
            so.data.bloodDonations = sub();
            so.data.deathCardUses = sub();
            so.data.arcadesVisited = sub();
            so.data.bomb = sub();
            so.data.timesDied = sub();
            so.data.rocksBombed = sub();
            so.data.collectionScreen = sub(true);
            so.data.boss = sub(true);
            so.data.levelsCompleted = sub(true);
            so.data.mwin = sub(true);
            so.data.rox = sub();
            so.data.polaroidCounter = sub();
          }
        }
        checker1 = checker2[0].split('');
        e = 0;
        while (e < 100) {
          if (!SecretUnlocked[e]) {
            f1 = e * 2 + 11;
            f2 = checker[f1] * 1 + (e % 4) * 1 + 1;
            if (f2 > 9) {
              f2 -= 9;
            }
            if (f2 == checker1[f1]) {
              uSecretUnlocked[e] = true;
              SecretUnlocked[e] = uSecretUnlocked[e];
              _root.lockor.unshift(e);
            }
          }
          ++e;
        }
      }
    }

    function soundy(nam, vol, xxasda) {
      lastn = nam;
      if (_root.soundonce[nam] == undefined or xxasda) {
        _root.soundonce[nam] = true;
        if (!so.data.soff or xxasda) {
          mpp = nam.indexOf('.mp3') <= 0;
          if (nam.indexOf('.mp') > 0 && mpp) {
            nam += '3';
          }
          mpp = true;
          if (vol == undefined) {
            vol = 100;
          }
          vol *= _root.soundvol;
          v0 = _root.sz.length;
          f1 = false;
          f2 = f1;
          if (_root.bossRoom == _root.lev or _root.bossRoom2 == _root.lev) {
            if (nam == 'bossintro.mp3' && _root.floorNum == 6) {
              f1 = true;
              nam = 'm10-0.mp3';
              _root.bossmusic = true;
            } else {
              if (nam == 'bossintro.mp3' && _root.floorNum == 8) {
                f1 = true;
                nam = 'm8-0.mp3';
                _root.bossmusic = true;
              } else {
                if (nam == 'bossintro.mp3' && _root.floorNum == 9 && !_root.altchap) {
                  f1 = true;
                  nam = 'm20-0.mp3';
                  _root.bossmusic = true;
                }
              }
            }
          }
          ++_root.szz;
          _root.sz[v0] = _root.attachMovie('soundz', 'sz' + _root.szz, _root.szz + 2000000000);
          _root.sz[v0].nam = nam;
          _root.sz[v0].s = new Sound(_root.sz[v0]);
          if (mpp) {
            _root.sz[v0].s.attachSound(nam);
          } else {
            _root.sz[v0].s.loadSound(nam, false);
          }
          z = 0;
          while (z < 40) {
            if (nam == 'm' + z + '-1.mp3') {
              f1 = true;
              f2 = true;
              if (z == 19) {
                vol = 0;
              }
            }
            if (nam == 'm' + z + '-0.mp3') {
              f1 = true;
            }
            ++z;
          }
          if (f1 or nam == 'bossintro.mp3' or nam == 'isaacbosswin.mp3' or nam == 'ambushwin.mp3' or nam == 'levelbumper.mp3' or nam == 'm1-2.mp3' or nam == bosm or nam == 'm-b0.mp3' or nam == 'm-b1.mp3' or nam == 'isaactitleloop.mp3' or nam == 'credits1-0.mp3' or nam == 'credits1-1.mp3') {
            if (nam == 'bossintro.mp3') {
              _root.bossmusic = true;
            }
            if (_root.musc != undefined) {
              _root.fade = true;
            }
            if (nam == 'isaacbosswin.mp3' or nam == 'ambushwin.mp3') {
              _root.sz[v0].wining = true;
            }
            if (_root.amusc == undefined) {
              if (f2 or nam == 'm-b1.mp3' or nam == 'isaactitleloop.mp3') {
                _root.sz[v0].looper = true;
                _root.sz[v0].s.start(lop, 0);
              } else {
                _root.sz[v0].s.start(0, 0);
              }
              _root.amusc = _root.sz[v0];
              vol = mvol;
            }
            _root.sz[v0].s.setVolume(vol);
            return _root.sz[v0];
          }
          if (nam.indexOf('loop') > 0) {
            _root.sz[v0].s.start(0, 999999);
            _root.sz[v0].looper2 = true;
          } else {
            _root.sz[v0].s.start(0, 0);
          }
          if (nam.indexOf('Lightning_Zap') > 0) {
            light.dones = true;
            light = _root.sz[v0];
          }
          _root.sz[v0].s.setVolume(vol);
          return _root.sz[v0];
        }
      }
    }

    function soz() {
      so = SharedObject.getLocal('so', '/');
      if (so.data.qqal == undefined) {
        qua('MEDIUM');
      } else {
        qua(so.data.qqal);
      }
      _root.musicoff = so.data.moff;
      if (so.data.momKills == undefined) {
        so.data.momKills = 0;
      }
      if (so.data.rox == undefined) {
        so.data.rox = 0;
      }
      if (so.data.polaroidCounter <= 0) {
        so.data.polaroidCounter = 0;
      }
      if (so.data.poopsDestroyed == undefined) {
        so.data.poopsDestroyed = 0;
      }
      if (so.data.bloodDonations == undefined) {
        so.data.bloodDonations = 0;
      }
      if (so.data.deathCardUses == undefined) {
        so.data.deathCardUses = 0;
      }
      if (so.data.arcadesVisited == undefined) {
        so.data.arcadesVisited = 0;
      }
      if (so.data.bomb == undefined) {
        so.data.bomb = 0;
      }
      if (so.data.timesDied == undefined) {
        so.data.timesDied = 0;
      }
      if (so.data.rocksBombed <= 0) {
        so.data.rocksBombed = 0;
      }
      if (so.data.collectionScreen == undefined) {
        so.data.collectionScreen = [];
      }
      if (so.data.lock == undefined) {
        so.data.lock = [];
      }
      if (so.data.lockor == undefined) {
        so.data.lockor = [];
      }
      if (so.data.ulock == undefined) {
        so.data.ulock = [];
      }
      if (so.data.boss == undefined) {
        so.data.boss = [];
      }
      if (so.data.levelsCompleted == undefined) {
        so.data.levelsCompleted = [0, 0, 0, 0, 0, 0, 0, 0, 0, 0];
      }
      if (so.data.mwin == undefined) {
        so.data.mwin = [0, 0, 0, 0, 0, 0, 0, 0, 0, 0];
      }
      _root.minibossBeaten = so.data.mwin;
      f1 = [];
      e = 0;
      while (e < 100) {
        f1[e] = so.data.lock[e];
        ++e;
      }
      so.data.lock = [];
      e = 0;
      while (e < 100) {
        so.data.lock[e] = f1[e];
        ++e;
      }
      _root.SecretUnlocked = so.data.lock;
      _root.lockor = so.data.lockor;
      _root.uSecretUnlocked = so.data.ulock;
      _root.res = so.data.res;
      if (so.data.wind == undefined) {
        _root.hdd = true;
      } else {
        _root.hdd = so.data.wind;
      }
      aloc2();
      aloc();
      if (so.data.collectionScreen == undefined) {
        so.data.collectionScreen = [];
      }
      if (so.data.lock == undefined) {
        so.data.lock = [];
      }
      if (so.data.lockor == undefined) {
        so.data.lockor = [];
      }
      if (so.data.ulock == undefined) {
        so.data.ulock = [];
      }
      if (so.data.boss == undefined) {
        so.data.boss = [];
      }
      if (so.data.levelsCompleted == undefined) {
        so.data.levelsCompleted = [0, 0, 0, 0, 0, 0, 0, 0, 0, 0];
      }
      if (so.data.mwin == undefined) {
        so.data.mwin = [0, 0, 0, 0, 0, 0, 0, 0, 0, 0];
      }
      _root.collectedItem = so.data.collectionScreen;
      _root.bossKilled = so.data.boss;
      _root.levelsCompleted = so.data.levelsCompleted;
    }

    function unlos() {
      --loslol;
      if (loslol < 0) {
        _root.unl.gogo = false;
        f1 = 0;
        f3 = 1000;
        for (z in _root.SecretUnlocked) {
          if (_root.SecretUnlocked[z] && !_root.uSecretUnlocked[z]) {
            f4 = z;
            if (f4 < f3) {
              f3 = f4;
              f1 = z;
            }
          }
        }
        if (f1 == 0) {
        } else {
          _root.unl.nogo = true;
          _root.unl.gotoAndPlay(4);
          _root.uSecretUnlocked[f1] = true;
          _root.lockor.unshift(f1);
          _root.unlll = f3;
          _root.unl.gotoAndPlay(2);
          _root.soundy('Choir_unlock.wav', 100);
          loslol = 90;
          if (acnam[f1] != 0) {
            callit(acnam[f1]);
          }
        }
      }
      if (_root._currentframe > 2) {
        _root.gameClears = so.data.momKills;
        if (_root.gameClears >= 2) {
          _root.SecretUnlocked[8] = true;
        }
        if (_root.gameClears >= 3) {
          _root.SecretUnlocked[9] = true;
        }
        if (_root.gameClears >= 4) {
          _root.SecretUnlocked[10] = true;
        }
        if (_root.gameClears >= 5) {
          _root.SecretUnlocked[11] = true;
        }
        if (_root.gameClears >= 6) {
          _root.SecretUnlocked[42] = true;
        }
        if (_root.gameClears >= 7) {
          _root.SecretUnlocked[43] = true;
        }
        if (_root.gameClears >= 8) {
          _root.SecretUnlocked[44] = true;
        }
        if (_root.gameClears >= 9) {
          _root.SecretUnlocked[45] = true;
        }
        if (_root.gameClears >= 10) {
          _root.SecretUnlocked[12] = true;
          _root.SecretUnlocked[41] = true;
        }
        z = 0;
        while (z < 3) {
          _root.SecretUnlocked[z + 15] = _root.SecretUnlocked[z + 1];
          ++z;
        }
        if (_root.SecretUnlocked[54]) {
          _root.SecretUnlocked[56] = true;
          _root.SecretUnlocked[57] = true;
        }
      }
    }

    function soundfra() {
      _root.soundonce = [];
      if (Key.isDown(77)) {
        if (nomute) {
          nomute = false;
          _root.musicoff = !_root.musicoff;
        }
      } else {
        nomute = true;
      }
      if (_root.musc == undefined) {
        _root.musc = _root.amusc;
        _root.amusc = undefined;
      }
      so.data.moff = _root.musicoff;
      if (_root.musc.nam == 'bossintro.mp3' && _root.musc.s.position > 4000) {
        fade = true;
      }
      if (_root.a.flyshut > 0) {
        if (_root.flyss == undefined) {
          _root.flyss = _root.soundy('insect_swarm_loop.wav', 100);
        }
        _root.flyss.s.setVolume(Math.min(150, _root.a.flyshut * 30 + 30));
      } else {
        _root.flyss.dones = true;
        _root.flyss = undefined;
      }
      if (_root.dmusic && (_root.a.player.hp > 0 or _root._currentframe != 2)) {
        _root.dmusic = false;
        _root.fade = true;
      }
      if (_root.amas && !_root.amusic) {
        _root.amas = false;
        _root.fade = true;
      }
      if (_currentframe == 2 && _root.musc.nam == 'm1-2.mp3') {
        _root.fade = false;
      }
      if (_root.musicoff or _root.fade) {
        f1 = _root.musc.s.getVolume();
        if (f1 > 5) {
          _root.musc.s.setVolume(f1 - 5);
        } else {
          _root.musc.done = true;
          _root.musc = undefined;
          _root.fade = false;
          if (introz or intro == 2) {
            introz = false;
          } else {
            intro = true;
          }
        }
      } else {
        if (_currentframe != 1 && _root._currentframe <= 5 or _currentframe == 20 or _currentframe == 21 or _currentframe == 24 or _currentframe == 41) {
          f10 = _root._currentframe == 2 && _root.lev == _root.libraryRoom or _root._currentframe == 24;
          f9 = _root._currentframe == 2 && _root.lev == _root.secretRoom2;
          f5 = _root._currentframe == 2 && _root.lev == _root.arcadeRoom;
          f6 = _root._currentframe == 2 && _root.lev == _root.shopl && _root.lev != _root.minibossRoom;
          f7 = _root._currentframe == 2 && _root.lev == 166 && _root.krampusFought != _root.floorNum;
          f8 = _root._currentframe == 2 && _root.lev == _root.secretRoom && _root.lev != _root.minibossRoom;
          if (_root.musc == undefined && _root.amusc == undefined) {
            --menubeen;
            if (f10) {
              if (intro) {
                soundy('m30-0.mp3');
                intro = false;
              } else {
                soundy('m30-1.mp3');
              }
            } else {
              if (f9) {
                if (intro) {
                  soundy('m28-0.mp3');
                  intro = false;
                } else {
                  soundy('m28-1.mp3');
                }
              } else {
                if (f8) {
                  if (intro) {
                    soundy('m15-0.mp3');
                    intro = false;
                  } else {
                    soundy('m15-1.mp3');
                  }
                } else {
                  if (f7) {
                    if (intro) {
                      soundy('m14-0.mp3');
                      intro = false;
                    } else {
                      soundy('m14-1.mp3');
                    }
                  } else {
                    if (f6) {
                      if (intro) {
                        soundy('m13-0.mp3');
                        intro = false;
                      } else {
                        soundy('m13-1.mp3');
                      }
                    } else {
                      if (f5) {
                        if (intro) {
                          soundy('m12-0.mp3');
                          intro = false;
                        } else {
                          soundy('m12-1.mp3');
                        }
                      } else {
                        if (_root._currentframe == 20 or _root._currentframe == 21) {
                          if (so.data.momKills > 9) {
                            if (intro) {
                              soundy('m11-0.mp3');
                              intro = false;
                            } else {
                              soundy('m11-1.mp3');
                            }
                          } else {
                            if (intro) {
                              soundy('credits1-0.mp3');
                              intro = false;
                            } else {
                              soundy('credits1-1.mp3');
                            }
                          }
                        } else {
                          if (_root._currentframe == 5) {
                            soundy('isaactitleloop.mp3');
                          } else {
                            if (_root.bossmusic && !_root.dmusic) {
                              if (_root.a.ashut > 0.9 or _root._currentframe == 4) {
                                f1 = _root.lev == _root.bossRoom or _root.bossRoom2 == _root.lev;
                                if (_root.floorNum == 11 or _root.floorNum == 9 && _root.altchap) {
                                  if (_root.intro) {
                                    soundy('m29-0.mp3');
                                    _root.intro = false;
                                  } else {
                                    soundy('m29-1.mp3');
                                  }
                                } else {
                                  if (_root.floorNum == 6 && f1) {
                                    soundy('m10-1.mp3');
                                  } else {
                                    if (_root.floorNum == 8 && f1) {
                                      soundy('m8-1.mp3');
                                    } else {
                                      if (_root.floorNum == 9 && f1 && !_root.altchap) {
                                        soundy('m20-1.mp3');
                                      } else {
                                        if (_root.altchap) {
                                          if (_root.intro) {
                                            soundy('m26-0.mp3');
                                            _root.intro = false;
                                          } else {
                                            soundy('m26-1.mp3');
                                          }
                                        } else {
                                          if (_root.intro) {
                                            soundy('m-b0.mp3');
                                            _root.intro = false;
                                          } else {
                                            soundy('m-b1.mp3');
                                          }
                                        }
                                      }
                                    }
                                  }
                                }
                                bosm = lastn;
                              } else {
                                if (_currentframe == 24) {
                                  if (_root.intro) {
                                    soundy('m30-0.mp3');
                                    intro = false;
                                  } else {
                                    soundy('m30-1.mp3');
                                  }
                                } else {
                                  if (_root.intro == 2) {
                                    soundy('m9-1.mp3');
                                  } else {
                                    if (_root.intro) {
                                      if (_root.a.fra > 50) {
                                        if (_root.lev == _root.bossRoom or _root.bossRoom2 == _root.lev) {
                                          soundy('isaacbosswin.mp3', 35);
                                        } else {
                                          soundy('ambushwin.mp3', 85);
                                        }
                                      }
                                      _root.intro = 2;
                                    } else {
                                      soundy('m9-1.mp3');
                                    }
                                  }
                                }
                              }
                            } else {
                              f1 = Math.min(Math.round(_root.floorNum / 2), 4);
                              if (f1 <= 0) {
                                f1 = 1;
                              }
                              if (_root.altchap && f1 != 4) {
                                f1 += 20;
                              }
                              if (_root.floorNum == 9) {
                                if (_root.altchap) {
                                  f1 = 25;
                                } else {
                                  f1 = 19;
                                }
                              }
                              if (_root.dmusic) {
                                _root.bossmusic = false;
                                f1 = 7;
                              } else {
                                if (_root.amusic) {
                                  f1 = 6;
                                  if (_root.lev == _root.arenaRoom && _root.bossArena or (_root.lev == _root.shopl or _root.lev == _root.minibossRoom) && _root.superSin) {
                                    f1 = 27;
                                  }
                                  if (_root.lev != arenaRoom) {
                                    _root.amas = true;
                                  }
                                }
                              }
                              if (_root.floorNum == 11) {
                                if (intro) {
                                  soundy('m-b0.mp3');
                                  intro = false;
                                } else {
                                  soundy('m-b1.mp3');
                                }
                                _root.bossmusic = false;
                              } else {
                                if (intro) {
                                  soundy('m' + f1 + '-0.mp3');
                                  intro = false;
                                } else {
                                  soundy('m' + f1 + '-1.mp3');
                                }
                              }
                            }
                          }
                        }
                      }
                    }
                  }
                }
              }
            }
          } else {
            if (_root.mmus == undefined && _root.musc.s.getVolume() < mvol) {
              if (!_root.musc.wait) {
                f11 = Math.min(_root.musc.s.getVolume() + 1, mvol);
                _root.musc.s.setVolume(f11);
              }
            }
          }
          if (_root.musc.nam != undefined && !fader) {
            if (_root.bossmusic) {
              if (_root.lev != _root.bossRoom && _root.bossRoom2 != _root.lev && _root.lev != _root.arcadeRoom && (_root.lev != 166 or _root.krampusFought != _root.floorNum) && _root.lev != _root.minibossRoom && _root.lev != _root.arenaRoom && _root._currentframe != 4) {
                _root.bossmusic = false;
                fade = true;
              }
              if (_root.a.ashut == 0 && _root.musc.nam != 'm9-0.mp3' && _root.musc.nam != 'm9-1.mp3' && _root.a.fra > 20 && _root.bossmusic != 2) {
                _root.bossmusic = 2;
                fade = true;
              }
            }
            if (_currentframe != 5 && _root.musc.nam == 'isaactitleloop.mp3') {
              _root.fade = true;
            }
            if (_currentframe == 5 && _root.musc.nam != 'isaactitleloop.mp3') {
              _root.fade = true;
            }
            if (f5 && _root.musc.nam != 'm12-1.mp3' && _root.musc.nam != 'm12-0.mp3') {
              _root.fade = true;
            }
            if (!f5 && (_root.musc.nam == 'm12-1.mp3' or _root.musc.nam == 'm12-0.mp3')) {
              _root.fade = true;
            }
            if (f6 && _root.musc.nam != 'm13-0.mp3' && _root.musc.nam != 'm13-1.mp3') {
              _root.fade = true;
            }
            if (!f6 && (_root.musc.nam == 'm13-0.mp3' or _root.musc.nam == 'm13-1.mp3')) {
              _root.fade = true;
              introz = true;
            }
            if (f7 && _root.musc.nam != 'm14-0.mp3' && _root.musc.nam != 'm14-1.mp3') {
              _root.fade = true;
            }
            if (!f7 && (_root.musc.nam == 'm14-0.mp3' or _root.musc.nam == 'm14-1.mp3')) {
              _root.fade = true;
            }
            if (f8 && _root.musc.nam != 'm15-0.mp3' && _root.musc.nam != 'm15-1.mp3') {
              _root.fade = true;
            }
            if (!f8 && (_root.musc.nam == 'm15-0.mp3' or _root.musc.nam == 'm15-1.mp3')) {
              _root.fade = true;
              introz = true;
            }
            if (f9 && _root.musc.nam != 'm28-0.mp3' && _root.musc.nam != 'm28-1.mp3') {
              _root.fade = true;
            }
            if (!f9 && (_root.musc.nam == 'm28-0.mp3' or _root.musc.nam == 'm28-1.mp3')) {
              _root.fade = true;
              introz = true;
            }
            if (f10 && _root.musc.nam != 'm30-0.mp3' && _root.musc.nam != 'm30-1.mp3') {
              _root.fade = true;
            }
            if (!f10 && (_root.musc.nam == 'm30-0.mp3' or _root.musc.nam == 'm30-1.mp3')) {
              _root.fade = true;
              introz = true;
            }
            if (_currentframe != 20 && _currentframe != 21 && (_root.musc.nam == 'credits1-0.mp3' or _root.musc.nam == 'credits1-1.mp3' or _root.musc.nam == 'm11-0.mp3' or _root.musc.nam == 'm11-1.mp3')) {
              _root.fade = true;
            }
            if ((_currentframe == 20 or _currentframe == 21) && (_root.musc.nam != 'credits1-0.mp3' && _root.musc.nam != 'credits1-1.mp3' && _root.musc.nam != 'm11-0.mp3' && _root.musc.nam != 'm11-1.mp3')) {
              _root.fade = true;
            }
          }
        } else {
          fade = true;
        }
      }
      for (e in sz) {
        trg = sz[e];
        if (trg.dones) {
          f1 = trg.s.getVolume() - 20;
          trg.s.setVolume(f1);
          if (f1 < 20) {
            trg.done = true;
          }
        }
        if (trg.looper && trg.s.duration - lop2 < trg.s.position) {
          trg.s.stop();
          trg.s.start(lop, 0);
        }
        if (_root.musc == trg && trg.s.duration - lop2 < trg.s.position) {
          trg.s.stop();
          trg.done = true;
          _root.musc = undefined;
        }
        if (_root.musc == trg && trg.wining && trg.s.duration - 2500 < trg.s.position) {
          _root.musc = undefined;
        }
        if (_root.mmus == trg && trg.s.duration - 1000 < trg.s.position) {
          _root.mmus = undefined;
        }
        if (trg.s.duration == trg.s.position && !trg.looper && !trg.looper2 or trg.done) {
          if (_root.mmus == trg) {
            _root.mmus = undefined;
          }
          if (_root.musc == trg) {
            _root.musc = undefined;
          }
          trg.s.stop();
          trg.swapDepths(100);
          removeMovieClip(trg);
          sz.splice(e, 1);
        }
      }
      if (random(1000) == 0) {
        f1 = [];
        e = 0;
        while (e < sz.length) {
          f1[e] = sz[e];
          ++e;
        }
        sz = [];
        e = 0;
        while (e < f1.length) {
          sz[e] = f1[e];
          ++e;
        }
      }
      if (_root.mmus != undefined) {
        _root.musc.s.setVolume(Math.max(5, _root.musc.s.getVolume() - 7));
      }
    }

    function prelod() {
      lod = _root.getBytesLoaded();
      tot = _root.getBytesTotal();
      v1 = Math.round((lod / tot) * 100);
      v2 = (v1 - cent) * 0.5;
      v3 = 100;
      if (Key.isDown(65)) {
        v3 += 5;
      }
      cent += Math.min(v3, v2);
      if (_currentframe != 1) {
        prelod = undefined;
      }
      if (cent > 99.5) {
        v1 = passw.toLowerCase();
        _root.gotoAndStop('intro');
      } else {}
    }

    function fullf(f1) {
      if (linx) {
        hdd = true;
        _root._xscale = 125;
        _root._yscale = 125;
        _root.a.mapd();
        _root._x = (1 - _root._xscale / 125) * 800 / 2;
        _root._y = (1 - _root._yscale / 125) * 600 / 2;
      } else {
        lasf = fra;
        if (f1) {
          so.data.full = !so.data.full;
        }
        fscommand('allowscale', 'false');
        if (_root.res <= 0 or !win) {
          if (!wider) {
            if (wid > 1000) {
              _root.res = 6;
            } else {
              _root.res = 1;
            }
          } else {
            if (wid > 1200) {
              if (wider == 2) {
                _root.res = 5;
              } else {
                _root.res = 4;
              }
            } else {
              _root.res = 2;
            }
          }
        }
        if (so.data.full) {
          f2 = refs[_root.res][0];
          f3 = refs[_root.res][1];
          mdm.Forms.thisForm.showFullScreen(true);
          if (win) {
            mdm.System.DirectX.enable(f2, f3, colz);
            mdm.Forms.thisForm.hideCaption(true);
          }
          if (f2 >= 1000 && f3 >= 800) {
            _root._xscale = 166.7;
          } else {
            if (f2 >= 800 && f3 >= 700) {
              _root._xscale = 154;
            } else {
              if (f2 >= 720 && f3 >= 600) {
                _root._xscale = 125;
              } else {
                _root._xscale = 100;
              }
            }
          }
        } else {
          mdm.Forms.thisForm.showFullScreen(false);
          mdm.Application.restore();
          if (win) {
            mdm.System.DirectX.disable();
            mdm.Forms.thisForm.hideCaption(false);
          }
          if (hdd == 2) {
            mdm.Forms.thisForm.width = 1024;
            mdm.Forms.thisForm.height = 800;
            _root._xscale = 163.5;
          } else {
            if (hdd) {
              mdm.Forms.thisForm.width = 800;
              mdm.Forms.thisForm.height = 620;
              _root._xscale = 125;
            } else {
              mdm.Forms.thisForm.width = 640;
              mdm.Forms.thisForm.height = 510;
              _root._xscale = 100;
            }
          }
        }
        _root._yscale = _root._xscale;
        _root.a.mapd();
        _root._x = (1 - _root._xscale / 125) * 800 / 2;
        _root._y = (1 - _root._yscale / 125) * 600 / 2;
        if (!so.data.full) {
          f1 = mdm.System.getResolution();
          mdm.Forms.thisForm.x = (f1[0] - mdm.Forms.thisForm.width) / 2 - 2;
          mdm.Forms.thisForm.y = (f1[1] - mdm.Forms.thisForm.height) / 2 - 20;
        }
      }
    }

    function callit(f1) {
      if (!linx) {
        var v2 = mdm.Application.path;
        if (win) {
          var v3 = mdm.Process.create('My App', 0, 0, 500, 600, '', v2 + 'FlashAchievements.exe ' + f1, v2, 2, 4);
        } else {
          if (fuk) {
            mdm.Process.setParams(f1);
            f1 = '';
          } else {
            f1 = ' ' + f1;
          }
          fuk = !fuk;
          var v3 = mdm.Process.create('My App', 0, 0, 500, 600, '', v2 + 'FlashAchievements ' + f1, v2, 2, 4);
        }
      }
    }

    function doit(trg) {
      switch (trg._name) {
        case 'b4':
          so.data.frog = !so.data.frog;
          break;
        case 'b3':
          so.data.left = !so.data.left;
          break;
        case 'b0':
          fullf(true);
          break;
        case 'b1':
          so.data.soff = !so.data.soff;
          break;
        case 'b2':
          _root.musicoff = !_root.musicoff;
      }
    }

    function wiq(f1) {
      _root.hdd = f1;
      so.data.wind = _root.hdd;
      showit();
      fullf();
    }

    function reser(f1) {
      if (win) {
        f2 = refs[f1];
        _root.res = f1;
        so.data.res = _root.res;
        showit();
        if (so.data.full) {
          fullf();
        }
      }
    }

    function showit() {
      trg = _root.paus;
      _root.paus.b0.gotoAndStop(1);
      _root.paus.b1.gotoAndStop(1);
      _root.paus.b2.gotoAndStop(1);
      _root.paus.b3.gotoAndStop(1);
      _root.paus.b4.gotoAndStop(1);
      trg.wq0.gotoAndStop(2);
      trg.wq1.gotoAndStop(2);
      trg.wq2.gotoAndStop(2);
      if (_root.hdd == 2) {
        trg.wq0.gotoAndStop(1);
      } else {
        if (_root.hdd) {
          trg.wq1.gotoAndStop(1);
        } else {
          trg.wq2.gotoAndStop(1);
        }
      }
      if (!so.data.full) {
        _root.paus.b0.gotoAndStop(2);
      }
      if (!so.data.soff) {
        _root.paus.b1.gotoAndStop(2);
      }
      if (!so.data.frog) {
        _root.paus.b4.gotoAndStop(2);
      }
      if (!so.data.left) {
        _root.paus.b3.gotoAndStop(2);
      }
      if (_root.musicoff) {
        _root.paus.b2.gotoAndStop(2);
      }
      trg.r0.gotoAndStop(_root.res);
      e = 1;
      while (e < 8) {
        trg2 = trg['r' + e];
        trg2.gotoAndStop(e);
        trg2.as._visible = e == _root.res;
        ++e;
      }
    }

    function qshow() {
      f1 = ['HIGH', 'MEDIUM', 'LOW', 'AUTO'];
      z = 0;
      while (z < 4) {
        trg = _root.paus['bq' + z];
        if (f1[z] == qqua or z == 3 && qqua == undefined) {
          trg.gotoAndStop(1);
        } else {
          trg.gotoAndStop(2);
        }
        ++z;
      }
    }

    function qua(f1) {
      qqua = so.data.qqal;
      if (f1) {
        qqua = f1;
      } else {
        if (qqua == 'AUTO') {
          qqua = 'HIGH';
        } else {
          if (qqua == 'MEDIUM') {
            qqua = 'LOW';
          } else {
            if (qqua == 'LOW') {
              qqua = 'AUTO';
            } else {
              qqua = 'MEDIUM';
            }
          }
        }
      }
      if (qqua == 'AUTO') {
        _quality = 'MEDIUM';
      } else {
        _quality = qqua;
      }
      _root.a.displayCornerMessage(qqua);
      so.data.qqal = qqua;
      qshow();
    }

    function goblack() {
      if (_currentframe >= 3 && _currentframe < 10) {
        f1 = _currentframe;
      } else {
        f1 = 0;
      }
      if (ala != f1) {
        ala = f1;
        overlay2._alpha = 100;
        _root.hud._visible = false;
      }
    }

    function colorit(trg, f1, f2, f3, f4, f5, f6) {
      var v1 = new flash.geom.ColorTransform();
      v1.redMultiplier = f1;
      v1.greenMultiplier = f2;
      v1.blueMultiplier = f3;
      v1.redOffset = f4;
      v1.greenOffset = f5;
      v1.blueOffset = f6;
      var v2 = new flash.geom.Transform(trg);
      v2.colorTransform = v1;
    }

    function uncolera() {
      trg2 = hud.it;
      if (itb >= 0) {
        if (itb % 5 == 0) {
          if (itb % 10 == 0) {
          } else {}
        }
      }
      --itb;
    }

    function darky(f1) {
      if (f1 != 150) {
        if (f1 > 0) {
          dark = f1;
        }
      } else {
        dark = 5;
        _root.men.men.pos = 4;
        fader = true;
        _root.musc.done = true;
        if (!_root.musicoff) {
          _root.soundy('m1-2.mp3');
        }
        _root.intro = true;
        _root.fade = false;
        _root.floorNum = 1;
      }
      if (dark > 0 or undark) {
        f1 = 2.5;
        f1 = getTimer() - dda;
        f1 /= 15;
        if (f1 > 15 or f1 <= 0) {
          f5 = 15;
        }
        if (fader) {
          dark += f1 * 2;
          if (dark > 160) {
            fader = false;
            _root.gotoAndStop('game');
          }
        }
        dark -= f1;
        undark = dark > 0;
        f1 = 1 - dark / 100;
        if (_root.floorNum == 9 && _root.altchap) {
          f2 = 255 * (1 - f1);
        } else {
          f2 = 0;
        }
        colo = new flash.geom.ColorTransform();
        colo.redMultiplier = f1;
        colo.greenMultiplier = f1;
        colo.blueMultiplier = f1;
        colo.redOffset = f2;
        colo.greenOffset = f2;
        colo.blueOffset = f2;
        var v4 = new flash.geom.Transform(this);
        v4.colorTransform = colo;
      } else {
        if (_root.a.fra < 50) {
          colo = new flash.geom.ColorTransform();
          var v4 = new flash.geom.Transform(this);
          v4.colorTransform = colo;
        }
      }
      dda = getTimer();
    }

    function onEnterFrame() {
      if (_currentframe == 2) {
        if (_root.paus != _root.hud.paus) {
          _root.paus = _root.hud.paus;
          aloc();
        }
      } else {
        if (_root.paus != _root.pauss) {
          aloc();
          _root.paus = _root.pauss;
        }
      }
      ++fra;
      if (fra % 100 == 10) {
        if (!linx) {
          var v2 = mdm.Application.path;
          mdm.FileSystem.saveFile(v2 + 'myFile.txt', '10');
        }
      }
      darky();
      soundfra();
      uncolera();
      if (overlay2._alpha > 0) {
        overlay2._alpha -= 7;
      } else {
        overlay2._alpha = 0;
      }
      if (Key.isDown(32) && (_currentframe == 3 && d._currentframe > 3 or _currentframe == 4 && d._currentframe > 21)) {
        _root.gotoAndStop('game');
        _root.fade = true;
      }
      if (Key.isDown(32) && _currentframe == 6) {
        _root.gotoAndStop(7);
        ffs1 = true;
      }
      if (Key.isDown(32) && (_currentframe == 21 or _currentframe == 7 or _root.creskip && _currentframe == 20) && !ffs1) {
        _root.creskip = false;
        _root.gotoAndStop('menu');
      }
      if (Key.isDown(32) && _currentframe == 9 && !ffs1) {
        _root.gotoAndStop(20);
        ffs1 = true;
      }
      if (Key.isDown(32) && (_currentframe > 9 && _currentframe < 20 or _currentframe == 22 or _currentframe == 23) && !ffs1) {
        _root.gotoAndStop(21);
        ffs1 = true;
      }
      if (!Key.isDown(32)) {
        ffs1 = false;
      }
      unlos();
      prelod();
      if (Key.isDown(73)) {
        if (unqua) {
          qua();
          unqua = false;
          _root.soundy('butt');
        }
      } else {
        unqua = true;
      }
      if (Key.isDown(72)) {
        if (unff2) {
          if (hdd == 2) {
            hdd = true;
          } else {
            if (hdd) {
              hdd = false;
            } else {
              hdd = 2;
            }
          }
          fullf();
          unff2 = false;
          so.data.wind = hdd;
        }
      } else {
        unff2 = true;
      }
      if (Key.isDown(70)) {
        if (unff) {
          if (!_root.a.unpause) {
            fullf(true);
            unff = false;
          }
        }
      } else {
        unff = true;
      }
    }

    linx = false;
    itemNames = [0, 'The Sad Onion', 'The Inner Eye', 'Spoon Bender', 'Max\'s Head', 'My Reflection', 'Number one', 'Blood of the Martyr', 'Brother Bobby', 'Skatole', 'Halo of Flies', '1up!', 'Magic Mushroom', 'The Virus', 'Roid Rage', '<3', 'Raw Liver', 'Skeleton Key', 'A dollar!', 'Boom!', 'Transcendence', 'The Compass', 'Lunch', 'Dinner', 'Dessert', 'Breakfast', 'Rotten Meat ', 'Wooden Spoon', 'The Belt', 'Moms Underwear', 'Moms Heels ', 'Moms Lipstick', 'Wire Coat hanger!', 'The Bible', 'The Book of Belial', 'The Necronomicon', 'The Poop!', 'Mr. Boom!', 'Tammys Head', 'Moms Bra', 'kamikaze!', 'Moms Pad ', 'Bobs Rotten Head', 'Pills here!', 'Teleport!', 'Yum Heart', 'Lucky Foot', 'Doctors Remote', 'Cupids arrow', 'Shoop da Whoop!', 'Steven', 'Pentagram', 'Dr Fetus', 'Magneto', 'Treasure Map', 'Moms Eye', 'Lemon Mishap', 'Distant Admiration', 'Book of shadows', 'Wiggle Worm', 'The Ladder', 'Tarot Card', 'Charm of the vampire', 'The Battery', 'Steam Sale', 'Anarchist Cookbook', 'The Hourglass', 'Sister Maggy', 'Technology', 'Chocolate Milk', 'Growth Hormones', 'Mini Mush', 'Rosary', 'Cube of Meat', 'A Quarter', 'PHD', 'Xray-Vision', 'My little Unicorn', 'Book of Revelations', 'The Mark', 'The Pact', 'Dead Cat', 'Lord of the Pit', 'the Nail', 'We need to go deeper!', 'Deck of Cards', 'Monstros Tooth', 'Lokis Horns', 'Lil Chubby', 'Spider Bite', 'The Small Rock', 'Spelunker Hat', 'Super Bandage', 'The Gamekid', 'Sack of pennies', 'Robo-Baby', 'Little Chad', 'The Book of Sin', 'The Relic', 'Little Gish', 'Little Steve', 'The Halo', 'Moms Bottle of Pills', 'The common cold', 'The Parasite', 'The Dice', 'Mr. Mega', 'The Pinking Shears', 'The Wafer', 'Money = Power', 'Moms Contacts', 'The Bean', 'Guardian Angel', 'Demon Baby', 'Moms Knife', 'Ouija Board', '9 Volt', 'Dead Bird', 'Brimstone', 'Blood Bag', 'Odd Mushroom', 'Odd Mushroom', 'Whore of Babylon', 'Monster Manuel', 'Dead Sea Scrolls', 'Bobby - Bomb', 'Razor Blade', 'Forget Me Now', 'Forever alone', 'Bucket of Lard', 'A Pony', 'Bomb Bag', 'A Lump of Coal', 'Guppys Paw', 'Guppys Tail', 'IV Bag', 'Best Friend', 'Remote Detonator', 'Stigmata', 'Moms Purse', 'Bobs Curse', 'Pageant Boy', 'Scapular', 'Speed Ball', 'Bum friend', 'Guppys Head', 'Prayer Card', 'Notched Axe', 'Infestation', 'Ipecac', 'Tough love', 'The Mulligan', 'Technology 2', 'Mutant Spider', 'Chemical peel', 'The Peeper!', 'Habit', 'Bloody Lust', 'Crystal Ball', 'Spirit of the night', 'Crack the Sky', 'Ankh', 'Celtic cross', 'Ghost Baby', 'The Candle', 'Cat-o-nine-tails', 'D20', 'Harlequin baby', 'Epic Fetus', 'Polyphemus', 'Daddy longlegs', 'Spider Butt', 'Sacrificial Dagger', 'Mitre', 'Rainbow Baby', 'Dads Key', 'Stem cells', 'Portable Slot!', 'Holy Water', 'Fate', 'The Black Bean', 'White Pony', 'Sacred Heart', 'Tooth Picks', 'Holy Grail', 'Dead Dove', 'Blood Rights', 'Guppys Hairball', 'Abel', 'SMB Super Fan!', 'Pyro', '3 Dollar bill', 'Telepathy for Dummies', 'MEAT!', 'Magic 8 ball', 'Moms coin purse', 'Squeezy', 'Jesus Juice', 'BOX'];
    itenDescriptions = [0, 'Tears up!', 'Triple Shot', 'Homing shots', 'Dmg up!', 0, 'Tears up!', 'Dmg up!', 0, 'Fly Love', 0, '1up!', 'All stats up!', 'Poison touch', 'Speed & Range up!', 'HP up!', 'HP up!', 0, '$$$', 0, 0, 0, 'HP up!', 'HP up!', 'HP up!', 'HP up!', 'HP up!', 'Speed up!', 'Speed up!', 'Range up!', 'Range up!', 'Range up!', 'Tears up!', 'SPACE to use', 'SPACE to use', 'SPACE to use', 'SPACE to use', 'SPACE to use', 'SPACE to use', 'SPACE to use', 'SPACE to use', 'SPACE to use', 'SPACE to use', 'SPACE to use', 'SPACE to use', 'SPACE to use', 0, 'SPACE to use', 'Piercing shots', 'SPACE to use', 'Damage Up', 'Damage Up', '???', 'Item snatcher', 0, 'Tears Up', 'SPACE to use', 'Attack Fly', 'SPACE to use', 'SSSSS!  ', 'Building Bridges', 0, 'kills heal', 'items recharge', '50% off', 'Space to Use', 0, 0, 'Laser Tears', 'Charge Shots', 'Speed + Dmg', 'Speed + Range', 'Faith Up!', 0, '+25 coins', 'better Pills!', 'Ive seen everything!', 'SPACE to use', 'SPACE to use', 'Dmg up!', 'Dmg up!', '9 lives', 'Deamon wings!', 'SPACE to use', 'SPACE to use', 'SPACE to use', 'SPACE to use', 'Tears Up', 0, 'Slow Effect', 'Dmg Up', 'see thru doors', '+2 hearts', 'SPACE to use', 'Gives Money', 0, 'Gives Hearts', 'SPACE to use', 0, 0, 0, 'all stats up', 'SPACE to use', 'Poison dmg', 'Split Shot', 'SPACE to use', 'Blast dmg', 'SPACE to use', 'dmg resistence', '$$$ = Damage', 'freeze effect', 'SPACE to use', 'Faith up', 0, 'Stab Stab Stab!', 'Spectral Tears', 'Quicker charge', 0, 0, 'HP Up', 'Fire rate up', 'Dmg up', 'Curse Up', 'SPACE to use', 'SPACE to use', 'Homing Bombs', 'SPACE to use', 'SPACE to use', 'Attack Fly', 'HP Up', 'SPACE to use', 'Gives Bombs', 'My Xmas Present', 'SPACE to use', 'Cursed?', 'Portable blood bank', 'Friends till the end!', 'SPACE to Detonate!', 'Dmg + Health +', 'more trinket room!', '+5 Poison Bombs', '', 'you have been blessed', 'Speed + Shot Speed +', 'hes greedy!', 'SPACE to use', 'SPACE to use', 'SPACE to use', 'They grow inside!', 'explosive shots!', 'tooth shot!', 'They grow inside!', 'laser!', 'Quad shot', 'damage up!', 'plop', 'Item Martyr ', 'RAGE!', 'SPACE to use', 'scary', 'SPACE to use', 'eternal life?', 'you feel blessed', '', 'SPACE to use', 'shot speed up!', 'SPACE to use', '', '', '', 'Daddys love', 'SPACE to use', '', 'you feel blessed', '', 'SPACE to use', 'health up', 'SPACE to use', 'Don\'t spill it', '', 'Panic Farts', 'SPACE to Use', 'Tears Up', 'Tears Up', 'Hp Up', 'Spectral Shots', 'SPACE to Use', 'Yuck!', '', 'All Stats Up', '', 'Random Tears', 'SPACE to use', 'Tears + HP Up', 'Tears Up', '', 'Tears Up', 'Range + Tears Up', '', '', '', 0];
    acnam = [0, 'Maggy', 'Cain', 'Judas', 'Killed_Mom', 0, 0, 0, 'The_Noose', 'The_Nail', 'The_Quarter', 'The_Fetus', 0, 'The_Spider', 'The_Spelunker', 0, 0, 0, 'The_Rock', 'Monstros_Tooth', 'Lil_Chubby', 'Lokis_Horns', 0, 0, 0, 'The_Bandage', 'The_Cross', 'The_Bag', 'The_Robo-Baby', 'Book_of_Sin', 'Gish', 'Steven', 'Chad', 'The_Gamekid', 'The_Halo', 'Mr_Mega', 'Pill_Bottle', 'Common_Cold', 'The_D6', 'The_Shears', 'The_Parasite', 'Baby', 'Terrible', 'The_Wafer', 'Money_Power', 'It_Lives', 'The_Bean', 'Moms_Contact', 'The_Necronomicon', 'Basement_Boy', 'Cave_Boy', 'Depths_Boy', 'Womb_Boy', 'Golden_God', 'Eve', 'Moms_Knife', 0, 0, 'The_Razor_Blade', 'The_Guardian_Angel', 'bombs', 'The_Demon_Baby', 'Forget_Me_Now', 'The_Monster_Manual', 'a_gift_from_krampus'];
    acnam.push('_d20', '_cross', '_abel', '_horn', '_knife2', '_rainbow', '_bloodlust', '_bloodpenny', '_bloodrights', '_polaroid', '_dadskey', '_toe', '_candle', '_burntpenny', '_tail', '_megafetus', '_fish', '_superfan', '_spiderbutt', '_counterfeit', '_hairball', '_eggsack', 0, '_samson', 0, '_platinum');
    acnam.push('_head', '_faith', '_eye', '_tongue', '_birdfoot', '_soul', '_lock', '_hand');
    fscommand('showmenu', 'false');
    fscommand('trapallkeys', 'true');
    stop();
    cent = 0;
    _root.sz = [];
    _root.szz = 0;
    _root.soundonce = [];
    _root.soundvol = 0.7;
    mvol = 35;
    dark = 0;
    lop = 0.03;
    checker = new Array(200);
    f1 = 5;
    f2 = 6;
    e = 0;
    while (e < 200) {
      checker[e] = 0;
      ++e;
    }
    e = 0;
    while (e < 1000) {
      f1 += f2;
      ++f2;
      if (f2 > 5) {
        f2 = 2;
      }
      if (f1 >= 200) {
        f1 -= 200;
      }
      checker[f1] += e % 5;
      if (checker[f1] >= 9) {
        checker[f1] -= 9;
      }
      ++e;
    }
    _root.collectedItem = [];
    soz();
    loslol = 0;
    intro = true;
    menubeen = 0;
    lop2 = 30;
    gof = 0;
    prelod();
    currUrl = _url.toLowerCase();
    pass = true;
    trg = _root.createEmptyMovieClip('olda', 299);
    old = new flash.display.BitmapData(640, 480, true, 0);
    trg.attachBitmap(_root.old, 1);
    trg = createEmptyMovieClip('mapa', 301);
    map = new flash.display.BitmapData(450, 150, true, 0);
    trg.attachBitmap(map, 1, true, false);
    trg._x = -45;
    overlay.swapDepths(500);
    if (!linx) {
      f1 = mdm.System.getResolution();
    }
    wid = f1[0];
    wider = f1[0] / f1[1];
    colz = f1[2];
    if (colz <= 10) {
      colz = 32;
    }
    if (wider <= 1.5) {
      wider = false;
    } else {
      if (wider > 1.7) {
        wider = 2;
      }
    }
    if (linx) {
      win = false;
    } else {
      var macVersion = mdm.System.macVerString;
      macVersion += ' ';
      win = macVersion.indexOf('type Function') > 0;
      mdm.Application.onAppChangeFocus = function (myObject) {
        if (myObject.focus == 'true') {
        } else {
          if (lasf + 100 < fra) {
            if (so.data.full) {
              so.data.full = false;
              fullf();
            }
          }
        }
      };

    }
    lasf = 0;
    refs = [0, [800, 600], [720, 480], [640, 480], [1280, 800], [1280, 720], [1024, 768]];
    overlay2._alpha = 0;
    ala = 0;
    attachMovie('hud', 'hud', 300);
    fullf();
    fra = 0;
    f1 = '';
    f3 = false;
    for (e in _root.SecretUnlocked) {
      if (_root.SecretUnlocked[e]) {
        if (acnam[e]) {
          if (f3) {
            f1 += ' ';
          }
          f1 += acnam[e];
          f3 = true;
        }
      }
    }
    if (f3) {
      callit(f1);
      if (!win) {
        callit(f1);
      }
    }
    var myMenu = new ContextMenu();
    myMenu.hideBuiltInItems();
    _root.menu = myMenu;
  }

  movieClip 5785  {
  }

  movieClip 5789  {
  }

  movieClip 5794  {
  }

  movieClip 5797  {
  }

  movieClip 5800  {
  }

  movieClip 5803  {
  }

  movieClip 5806  {
  }

  movieClip 5809  {
  }

  movieClip 5812  {
  }

  movieClip 5815  {
  }

  movieClip 5818  {
  }

  movieClip 5821  {
  }

  movieClip 5824  {
  }

  movieClip 5827  {
  }

  movieClip 5830  {
  }

  movieClip 5833  {
  }

  movieClip 5834  {

    frame 1 {
      if (_root.SecretUnlocked[90]) {
        gotoAndStop(14);
      } else {
        if (_root.so.data.momKills > 200) {
          gotoAndStop(15);
        } else {
          if (_root.SecretUnlocked[75]) {
            gotoAndStop(13);
          } else {
            if (_root.SecretUnlocked[53]) {
              gotoAndStop(7);
            } else {
              if (_root.so.data.polaroidCounter > 0) {
                gotoAndStop(Math.min(12, 7 + _root.so.data.polaroidCounter));
              } else {
                if (_root.SecretUnlocked[41]) {
                  gotoAndStop(6);
                } else {
                  if (_root.SecretUnlocked[45]) {
                    gotoAndStop(5);
                  } else {
                    if (_root.SecretUnlocked[42]) {
                      gotoAndStop(4);
                    } else {
                      if (_root.SecretUnlocked[3]) {
                        gotoAndStop(3);
                      } else {
                        if (_root.SecretUnlocked[4]) {
                          gotoAndStop(2);
                        } else {
                          gotoAndStop(1);
                        }
                      }
                    }
                  }
                }
              }
            }
          }
        }
      }
    }
  }

  movieClip 5840  {
  }

  movieClip 5842  {
  }

  movieClip 5872  {
  }

  movieClip 5886  {
  }

  movieClip 5936  {
  }

  movieClip 5938  {
  }

  movieClip 5939  {
  }

  movieClip 5940  {
  }

  movieClip 5948  {

    frame 1 {
      gotoAndStop(_root.characterID + 1);
    }
  }

  movieClip 5951  {
  }

  movieClip 5972  {

    frame 1766 {
      _root.gotoAndStop('menu');
    }
  }

  movieClip 6007  {

    frame 1079 {
      if (_root.so.data.momKills < 1) {
      }
    }

    frame 2457 {
      if (_root.so.data.momKills < 1) {
      }
    }

    frame 2940 {
      _root.gotoAndStop('menu');
    }
  }

  movieClip 6010  {
  }

  movieClip 6014  {
  }

  movieClip 6016  {
  }

  movieClip 6018  {
  }

  movieClip 6020  {
  }

  movieClip 6022  {
  }

  movieClip 6024  {
  }

  movieClip 6027  {
  }

  movieClip 6030  {
  }

  movieClip 6033  {
  }

  movieClip 6036  {
  }

  movieClip 6039  {
  }

  movieClip 6042  {
  }

  movieClip 6045  {
  }

  movieClip 6048  {
  }

  movieClip 6050  {
  }

  movieClip 6053  {
  }

  movieClip 6055  {
  }

  movieClip 6058  {
  }

  movieClip 6061  {
  }

  movieClip 6063  {
  }

  movieClip 6066  {
  }

  movieClip 6068  {
  }

  movieClip 6087  {
  }

  movieClip 6089  {
  }

  movieClip 6091  {
  }

  movieClip 6093  {
  }

  movieClip 6095  {
  }

  movieClip 6097  {
  }

  movieClip 6098  {
  }

  movieClip 6102  {

    frame 1 {
      gotoAndStop(_root.bossID);
    }
  }
  
  // unknown tag 88 length 148

  movieClip 6146  {

    frame 1 {
      gotoAndStop(_root.bossID);
    }
  }

  frame 2 {
    _root.goblack();
  }

  frame 2 {
    stop();
  }

  movieClip 6169  {
  }

  movieClip 6177  {

    frame 1 {
      gotoAndStop((_root.lev + _root.lev * _root.lev + _root.lev * _root.lev * _root.lev) % _totalframes + 1);
    }
  }

  movieClip 6185  {

    frame 1 {
      gotoAndStop((_root.lev + _root.lev * _root.lev + _root.lev * _root.lev * _root.lev) % _totalframes + 1);
    }
  }

  movieClip 6188  {
  }

  movieClip 6191  {
  }

  movieClip 6193  {
  }

  movieClip 6195  {
  }

  movieClip 6197  {
  }

  movieClip 6199  {
  }

  movieClip 6207  {

    frame 1 {
      gotoAndStop((_root.lev + _root.lev * _root.lev + _root.lev * _root.lev * _root.lev) % _totalframes + 1);
    }
  }

  movieClip 6209  {
  }

  movieClip 6211  {
  }

  movieClip 6213  {
  }

  movieClip 6215  {
  }

  movieClip 6217  {
  }

  movieClip 6219  {
  }

  movieClip 6221  {
  }

  movieClip 6223  {

    frame 1 {
      gotoAndStop((_root.lev + _root.lev * _root.lev + _root.lev * _root.lev * _root.lev) % _totalframes + 1);
    }
  }

  movieClip 6225  {

    frame 1 {
      gotoAndStop((_root.lev + _root.lev * _root.lev + _root.lev * _root.lev * _root.lev) % _totalframes + 1);
    }
  }

  movieClip 6229  {

    frame 1 {
      gotoAndStop((_root.lev + _root.lev * _root.lev + _root.lev * _root.lev * _root.lev) % _totalframes + 1);
    }
  }

  movieClip 6235  {
  }

  movieClip 6238  {
  }

  movieClip 6240  {

    frame 1 {
      stop();
    }
  }

  movieClip 6244  {
  }

  movieClip 6246  {
  }

  movieClip 6248  {
  }

  movieClip 6251  {

    frame 1 {
      gotoAndStop(random(_totalframes) + 1);
    }
  }

  movieClip 6255  {
  }

  movieClip 6262  {

    frame 1 {
      stop();
    }
  }

  movieClip 6267  {

    frame 1 {
      stop();
    }
  }

  movieClip 6272  {
  }

  movieClip 6275  {
  }

  movieClip 6277  {
  }

  movieClip 6279  {
  }

  movieClip 6282  {
  }

  movieClip 6284  {
  }

  movieClip 6286  {
  }

  movieClip 6291  {

    frame 1 {
      stop();
    }
  }

  movieClip 6295  {
  }

  movieClip 6297  {
  }

  movieClip 6301  {

    frame 1 {
      stop();
    }
  }

  movieClip 6303  {
  }

  movieClip 6304  {
  }

  movieClip 6307  {
  }

  movieClip 6309  {
  }

  movieClip 6311  {
  }

  movieClip 6313  {
  }

  movieClip 6315  {
  }

  movieClip 6317  {
  }

  movieClip 6318  {
  }

  movieClip 6320  {
  }

  movieClip 6322  {
  }

  movieClip 6325  {
  }

  movieClip 6326  {

    frame 1 {
      stop();
    }
  }

  movieClip 6331  {

    frame 1 {
      gotoAndStop(random(_totalframes) + 1);
    }
  }

  movieClip 6334  {
  }

  movieClip 6336  {
  }

  movieClip 6343  {

    frame 1 {
      gotoAndStop(random(_totalframes) + 1);
    }
  }

  movieClip 6348  {

    frame 1 {
      gotoAndStop(random(_totalframes) + 1);
    }
  }

  movieClip 6353  {

    frame 1 {
      gotoAndStop(random(_totalframes) + 1);
    }
  }

  movieClip 6356  {
  }

  movieClip 6358  {
  }

  movieClip 6360  {
  }

  movieClip 6362  {
  }

  movieClip 6364  {
  }

  movieClip 6366  {
  }

  movieClip 6372  {
  }

  movieClip 6382  {
  }

  movieClip 6384  {
  }

  movieClip 6385  {
  }

  movieClip 6388  {
  }

  movieClip 6391  {
  }

  movieClip 6392  {

    frame 1 {
      stop();
    }
  }

  movieClip 6394  {
  }

  movieClip 6396  {
  }

  movieClip 6397  {

    frame 9 {
      stop();
    }
  }

  movieClip 6398  {

    frame 14 {
      _root.soundy('Door_Heavy_Close.mp', 100);
    }

    frame 23 {
      stop();
    }
  }

  movieClip 6400  {
  }

  movieClip 6402  {
  }

  movieClip 6403  {

    frame 8 {
      stop();
    }
  }

  movieClip 6405  {
  }

  movieClip 6406  {

    frame 20 {
      stop();
    }
  }

  movieClip 6407  {

    frame 1 {
      k._rotation = -_parent._rotation - 90;
    }

    frame 27 {
      stop();
    }
  }

  movieClip 6408  {

    frame 11 {
      stop();
    }
  }

  movieClip 6410  {
  }

  movieClip 6412  {
  }

  movieClip 6414  {
  }

  movieClip 6416  {
  }

  movieClip 6417  {
  }

  movieClip 6418  {

    frame 19 {
      stop();
    }
  }

  movieClip 6419  {

    frame 11 {
      stop();
    }
  }

  movieClip 6421  {
  }

  movieClip 6423  {
  }

  movieClip 6424  {

    frame 42 {
      _parent.nextFrame();
    }
  }

  movieClip 6426  {
  }

  movieClip 6428  {
  }

  movieClip 6439  {
  }

  movieClip 6440  {

    frame 22 {
      stop();
    }
  }

  movieClip 6441  {
  }

  movieClip 6443  {
  }

  movieClip 6445  {
  }

  movieClip 6447  {
  }

  movieClip 6451  {
  }

  movieClip 6453  {
  }

  movieClip 6454  {

    frame 1 {
      if (_root.bossArena) {
        gotoAndStop(2);
      } else {
        gotoAndStop(1);
      }
    }
  }

  movieClip 6455  {

    frame 7 {
      _root.soundy('Door_Heavy_Open.mp', 100);
    }

    frame 21 {
      stop();
    }
  }

  movieClip 6456  {

    frame 5 {
      _root.soundy('Door_Heavy_Close.mp', 100);
    }

    frame 11 {
      stop();
    }
  }

  movieClip 6458  {
  }

  movieClip 6460  {
  }

  movieClip 6461  {

    frame 1 {
      k._rotation = -_parent._rotation - 90;
    }

    frame 27 {
      stop();
    }
  }

  movieClip 6462  {

    frame 14 {
      _root.soundy('Door_Heavy_Close.mp', 100);
    }

    frame 23 {
      stop();
    }
  }

  movieClip 6463  {

    frame 9 {
      stop();
    }
  }

  movieClip 6465  {
  }

  movieClip 6466  {

    frame 9 {
      stop();
    }
  }

  movieClip 6467  {

    frame 14 {
      _root.soundy('Door_Heavy_Close.mp', 100);
    }

    frame 23 {
      stop();
    }
  }

  movieClip 6469  {
  }

  movieClip 6470  {

    frame 42 {
      _parent.nextFrame();
    }
  }

  movieClip 6471  {

    frame 1 {
      stop();
    }
  }

  movieClip 6483  {
  }

  movieClip 6486  {
  }

  movieClip 6500  {
  }

  movieClip 6501  {
  }

  movieClip 6504  {
  }

  movieClip 6506  {

    frame 1 {
      _root.a.spawnb(this, -93);
    }
  }

  movieClip 6508  {

    frame 1 {
      e = 0;
      while (e < 50) {
        if (_name == 'a' + e) {
          f1 = true;
          _root.a.spawnb(this, -e * 0.01);
        }
        ++e;
      }
      if (!f1) {
        _root.a.spawnb(this, -0.01);
      }
    }
  }

  movieClip 6510  {

    frame 1 {
      e = 0;
      while (e < 100) {
        if (_name == 'a' + e) {
          _root.a.spawnb(this, e / 100);
          e = 101;
        }
        ++e;
      }
    }
  }

  movieClip 6512  {	//Golden Poop Spawner

    frame 1 {
      _root.a.spawnb(this, 1.4955);
    }
  }

  movieClip 6513  {

    frame 1 {
      _root.a.spawnb(this, -37);
    }
  }

  movieClip 6514  {

    frame 1 {
      _root.a.spawnb(this, -29);
    }
  }

  movieClip 6516  {

    frame 1 {
      _root.a.spawnb(this, 1);
    }
  }

  movieClip 6517  {

    frame 1 {
      _root.a.spawnb(this, -92);
    }
  }
  
  // unknown tag 88 length 63

  movieClip 6520  {

    frame 1 {
      _root.a.spawnb(this, -1);
    }
  }

  movieClip 6522  {

    frame 1 {
      _root.a.spawnb(this, 1.3);
    }
  }

  movieClip 6523  {

    frame 1 {
      _root.a.spawnb(this, -72);
    }
  }

  movieClip 6524  {

    frame 1 {
      _root.a.spawnb(this, -13);
    }
  }

  movieClip 6525  {

    frame 1 {
      _root.a.spawnb(this, -73);
    }
  }

  movieClip 6526  {

    frame 1 {
      _root.a.spawnb(this, -74);
    }
  }

  movieClip 6528  {

    frame 1 {
      e = 0;
      while (e < 20) {
        if (_name == 'a' + e) {
          f1 = true;
          _root.a.spawnb(this, -e * 0.01);
        }
        ++e;
      }
      if (!f1) {
        _root.a.spawnb(this, 3);
      }
    }
  }

  movieClip 6529  {

    frame 1 {
      _root.a.spawnb(this, -18);
    }
  }

  movieClip 6530  {

    frame 1 {
      _root.a.spawnb(this, -32);
    }
  }

  movieClip 6532  {

    frame 1 {
      _root.a.spawnb(this, -10);
    }
  }

  movieClip 6533  {

    frame 1 {
      _root.a.spawnb(this, -85);
    }
  }

  movieClip 6534  {

    frame 1 {
      _root.a.spawnb(this, -76);
    }
  }

  movieClip 6536  {

    frame 1 {
      _root.a.spawnb(this, -7);
    }
  }

  movieClip 6537  {

    frame 1 {
      _root.a.spawnb(this, -81);
    }
  }

  movieClip 6538  {

    frame 1 {
      _root.a.spawnb(this, -15);
    }
  }

  movieClip 6539  {

    frame 1 {
      _root.a.spawnb(this, -16);
    }
  }

  movieClip 6540  {

    frame 1 {
      _root.a.spawnb(this, -80);
    }
  }

  movieClip 6541  {

    frame 1 {
      _root.a.spawnb(this, -14);
    }
  }

  movieClip 6542  {

    frame 1 {
      _root.a.spawnb(this, -70);
    }
  }

  movieClip 6543  {

    frame 1 {
      _root.a.spawnb(this, -58);
    }
  }

  movieClip 6545  {

    frame 1 {
      e = 0;
      while (e < 20) {
        if (_name == 'a' + e) {
          f1 = true;
          _root.a.spawnb(this, -e * 0.01);
        }
        ++e;
      }
      if (!f1) {
        _root.a.spawnb(this, 1.93);
      }
    }
  }

  movieClip 6547  {

    frame 1 {
      _root.a.spawnb(this, -19);
    }
  }

  movieClip 6549  {

    frame 1 {
      _root.a.spawnb(this, 1.4);
    }
  }

  movieClip 6551  {		//Flaming Poop Spawner

    frame 1 {
      _root.a.spawnb(this, 1.49);
    }
  }

  movieClip 6552  {

    frame 1 {
      _root.a.spawnb(this, -77);
    }
  }

  movieClip 6553  {

    frame 1 {
      _root.a.spawnb(this, -79);
    }
  }

  movieClip 6554  {

    frame 1 {
      _root.a.spawnb(this, -78);
    }
  }

  movieClip 6556  {

    frame 1 {
      _root.a.spawnb(this, -10);
    }
  }

  movieClip 6557  {

    frame 1 {
      _root.a.spawnb(this, -84);
    }
  }

  movieClip 6558  {

    frame 1 {
      _root.a.spawnb(this, -20);
    }
  }

  movieClip 6559  {

    frame 1 {
      _root.a.spawnb(this, -53);
    }
  }

  movieClip 6560  {

    frame 1 {
      _root.a.spawnb(this, -35);
    }
  }

  movieClip 6561  {

    frame 1 {
      _root.a.spawnb(this, -31);
    }
  }

  movieClip 6562  {

    frame 1 {
      _root.a.spawnb(this, -56);
    }
  }

  movieClip 6564  {

    frame 1 {
      _root.a.spawnb(this, -27);
    }
  }

  movieClip 6565  {

    frame 1 {
      _root.a.spawnb(this, -26);
    }
  }

  movieClip 6566  {

    frame 1 {
      _root.a.spawnb(this, -21);
    }
  }

  movieClip 6567  {

    frame 1 {
      _root.a.spawnb(this, -30);
    }
  }

  movieClip 6568  {

    frame 1 {
      _root.a.spawnb(this, -55);
    }
  }

  movieClip 6569  {

    frame 1 {
      _root.a.spawnb(this, -22);
    }
  }

  movieClip 6570  {

    frame 1 {
      _root.a.spawnb(this, -57);
    }
  }

  movieClip 6573  {

    frame 1 {
      _root.a.spawnb(this, -9);
    }
  }

  movieClip 6574  {		//Poop Spawner

    frame 1 {
      _root.a.spawnb(this, 1.5);
    }
  }

  movieClip 6576  {

    frame 1 {
      _root.a.spawnb(this, -3);
    }
  }

  movieClip 6578  {

    frame 1 {
      _root.a.spawnb(this, -4);
    }
  }

  movieClip 6580  {

    frame 1 {
      _root.a.spawnb(this, -5);
    }
  }

  movieClip 6583  {
  }

  movieClip 6584  {

    frame 1 {
      stop();
    }
  }

  movieClip 6585  {

    frame 1 {
      _root.a.spawnb(this, -2);
    }
  }

  movieClip 6586  {

    frame 1 {
      _root.a.spawnb(this, -68);
    }
  }

  movieClip 6587  {

    frame 1 {
      _root.a.spawnb(this, -71);
    }
  }

  movieClip 6589  {

    frame 1 {
      _root.a.spawnb(this, -6);
    }
  }

  movieClip 6590  {

    frame 1 {
      _root.a.spawnb(this, -52);
    }
  }

  movieClip 6591  {
  }

  movieClip 6594  {

    frame 1 {
      _root.a.spawnb(this, -12);
    }
  }

  movieClip 6595  {

    frame 1 {
      _root.a.spawnb(this, -17);
    }
  }

  movieClip 6596  {

    frame 1 {
      _root.a.spawnb(this, -64);
    }
  }

  movieClip 6597  {

    frame 1 {
      _root.a.spawnb(this, -25);
    }
  }

  movieClip 6598  {

    frame 1 {
      _root.a.spawnb(this, -63);
    }
  }

  movieClip 6599  {
  }

  movieClip 6601  {

    frame 1 {
      _root.a.spawnb(this, -23);
    }
  }

  movieClip 6602  {

    frame 1 {
      _root.a.spawnb(this, -33);
    }
  }

  movieClip 6603  {

    frame 1 {
      _root.a.spawnb(this, 4);
    }
  }

  movieClip 6604  {

    frame 1 {
      _root.a.spawnb(this, -67);
    }
  }

  movieClip 6605  {

    frame 1 {
      _root.a.spawnb(this, -46);
    }
  }

  movieClip 6606  {

    frame 1 {
      _root.a.spawnb(this, -48);
    }
  }

  movieClip 6607  {
  }

  movieClip 6609  {

    frame 1 {
      _root.a.spawnb(this, -49);
    }
  }

  movieClip 6611  {

    frame 1 {
      _root.a.spawnb(this, -11);
    }
  }

  movieClip 6612  {

    frame 1 {
      _root.a.spawnb(this, -44);
    }
  }

  movieClip 6613  {

    frame 1 {
      _root.a.spawnb(this, -47);
    }
  }

  movieClip 6614  {

    frame 1 {
      _root.a.spawnb(this, -50);
    }
  }

  movieClip 6615  {

    frame 1 {
      _root.a.spawnb(this, -51);
    }
  }

  movieClip 6616  {

    frame 1 {
      _root.a.spawnb(this, -62);
    }
  }

  movieClip 6617  {

    frame 1 {
      _root.a.spawnb(this, -66);
    }
  }

  movieClip 6618  {

    frame 1 {
      _root.a.spawnb(this, -40);
    }
  }

  movieClip 6619  {

    frame 1 {
      _root.a.spawnb(this, -38);
    }
  }

  movieClip 6620  {

    frame 1 {
      _root.a.spawnb(this, -39);
    }
  }

  movieClip 6621  {

    frame 1 {
      _root.a.spawnb(this, -60);
    }
  }

  movieClip 6622  {

    frame 1 {
      _root.a.spawnb(this, -42);
    }
  }

  movieClip 6623  {

    frame 1 {
      _root.a.spawnb(this, -59);
    }
  }

  movieClip 6624  {
  }

  movieClip 6626  {

    frame 1 {
      _root.a.spawnb(this, -41);
    }
  }

  movieClip 6628  {

    frame 1 {
      _root.a.spawnb(this, -34);
    }
  }

  movieClip 6629  {

    frame 1 {
      _root.a.spawnb(this, -54);
    }
  }

  movieClip 6630  {
  }

  movieClip 6632  {

    frame 1 {
      _root.a.spawnb(this, -43);
    }
  }

  movieClip 6634  {

    frame 1 {
      _root.a.spawnb(this, -36);
    }
  }

  movieClip 6635  {

    frame 1 {
      _root.a.spawnb(this, -69);
    }
  }

  movieClip 6636  {

    frame 1 {
      _root.a.spawnb(this, -75);
    }
  }

  movieClip 6637  {

    frame 1 {
      _root.a.spawnb(this, -65);
    }
  }

  movieClip 6639  {
  }

  movieClip 6646  {

    frame 1 {
      gotoAndStop(random(_totalframes) + 1);
    }
  }

  movieClip 6653  {

    frame 1 {
      gotoAndStop(random(_totalframes) + 1);
    }
  }

  movieClip 6661  {
  }

  movieClip 6662  {

    frame 1 {
      _root.a.spawnb(this, -90);
    }
  }

  movieClip 6663  {

    frame 1 {
      _root.a.spawnb(this, -91);
    }
  }

  movieClip 6664  {

    frame 1 {
      _root.a.spawnb(this, -88);
    }
  }

  movieClip 6665  {
  }

  movieClip 6668  {

    frame 1 {
      _root.a.spawnb(this, 1.94);
    }
  }

  movieClip 6669  {

    frame 1 {
      _root.a.spawnb(this, 1.41);
    }
  }

  movieClip 6670  {
  }

  movieClip 6673  {		//Guarded Poop Spawner

    frame 1 {
      _root.a.spawnb(this, 1.495);
    }
  }

  movieClip 6674  {
  }

  movieClip 6676  {

    frame 1 {
      _root.a.spawnb(this, -83);
    }
  }

  movieClip 6677  {

    frame 1 {
      _root.a.spawnb(this, -82);
    }
  }

  movieClip 6678  {
  }

  movieClip 6680  {
  }

  movieClip 6682  {
  }

  movieClip 6684  {
  }

  movieClip 6685  {

    frame 1 {
      function horsch(trg) {
        if (_root.spacebarItem == 141) {
          trg.gotoAndStop(2);
        } else {
          trg.gotoAndStop(1);
        }
      }

      function slotReeler(trg) {
        trg.gotoAndStop(1);
        trg2 = trg._parent._parent._parent;
        if (trg2.s != 5) {
          trg2 = trg._parent._parent._parent._parent;
        }
        if (trg2.col == 41) {
          trg.gotoAndStop(2);
        }
      }

      function pffx(f1) {
        f2 = _root.levz[f1 + 1] + _root.levz[f1 - 1] + _root.levz[f1 + 10] + _root.levz[f1 - 10];
        if (_root.levz[f1] == 0 && f2 < 2 && f5 < f6 or f1 == 35) {
          _root.levz[f1] = 1;
          acts2.push(f1);
          ++f8;
          if (f1 != 35) {
            ++f5;
          }
        }
      }

      function hat(f1) {
        var v2 = 0;
        _root.hat[f1] = true;
        switch (f1) {
          case 10:
          case 11:
          case 12:
          case 31:
          case 37:
          case 40:
            v2 = 2;
            break;
          case 4:
          case 6:
          case 7:
          case 9:
          case 16:
          case 19:
          case 21:
          case 23:
          case 28:
          case 29:
          case 32:
          case 41:
          case 42:
          case 48:
          case 50:
          case 54:
            v2 = 5;
            break;
          case 2:
          case 5:
          case 20:
          case 30:
          case 34:
          case 52:
          case 53:
          case 58:
            v2 = 3;
            break;
          case 3:
          case 8:
          case 22:
          case 36:
          case 45:
          case 56:
          case 60:
          case 61:
            v2 = 4;
            break;
          case 26:
          case 24:
          case 27:
          case 33:
          case 35:
          case 39:
          case 42:
          case 44:
          case 51:
          case 55:
          case 58:
            v2 = 1;
            break;
          case 13:
          case 14:
          case 15:
          case 17:
          case 18:
          case 25:
          case 46:
          case 47:
          case 49:
          case 59:
            v2 = 0;
        }
        _root.hatmode[v2] = f1;
      }

      function gish(trg, f1) {
        if (f1 == 2) {
          if (trg._parent._parent == player or trg._parent._parent._parent == player or trg._parent._parent._parent._parent == player or trg._parent._parent._parent._parent._parent == player) {
            f1 = 3;
          }
        }
        if (f1 == 3) {
          trg.gotoAndStop(1);
        } else {
          if (f1) {
            if (altboss == 2) {
              trg.gotoAndStop(2);
            } else {
              trg.gotoAndStop(1);
            }
          } else {
            if (altboss == 2) {
              trg.gotoAndStop(3);
            } else {
              if (altboss) {
                trg.gotoAndStop(2);
              } else {
                trg.gotoAndStop(1);
              }
            }
          }
        }
      }

      function baseDamage() {
        var v2 = 0;
        if (belial) {
          v2 += 2;
        }
        if (haveEffect[7]) {
          ++v2;
        }
        if (haveEffect[90]) {
          ++v2;
        }
        if (haveEffect[109]) {
          v2 += _root.coins * 0.04;
        }
        if (haveEffect[122] > 0) {
          v2 += haveEffect[122] * haveEffect[122] * 1.5;
        }
        v2 += haveEffect[50] + haveEffect[51] + haveEffect[70] + haveEffect[79] + (haveEffect[80] + haveEffect[4] + haveEffect[197]) * 0.5 + (haveEffect[12] + haveEffect[101] + haveEffect[121] + haveEffect[138] + haveEffect[193] + haveEffect[189]) * 0.3;
        if (haveEffect[120]) {
          v2 *= 0.9;
          v2 -= 0.4;
        }
        if (demon > 0) {
          v2 += 0.7;
        }
        if (rage != 1) {
          v2 += rage - 1;
        }
        if (haveEffect[154]) {
          if (sob == -1 or _root.hat[11] && random(2) == 0) {
            v2 += 2;
          }
        }
        if (haveEffect[69] && !haveEffect[118]) {
          chal = Math.max(1, Math.min(5, 1 + (fra - chaf) / 10) * 1.8 - 2);
          v2 += (chal - 1) * 1.3;
        }
        v2 += razor * 0.6;
        v2 = 3.5 * Math.sqrt(1 + v2 * 1.2);
        if (haveEffect[169]) {
          if (haveEffect[2] == 1 or haveEffect[153]) {
            v2 += 5;
          } else {
            v2 += 4;
            v2 *= 2;
          }
        }
        var v3 = [0, 0, 0.2, 0.35, 0.05, -0.25, 0];
        v2 *= 1 + v3[_root.characterID];
        _root.tearDamage = v2;
        if (haveTrinket(35)) {
          v2 += 2;
        }
        if (haveEffect[182]) {
          v2 *= 2.3;
          ++v2;
        }
        if (haveEffect[152]) {
          v2 *= 0.65;
        }
        return v2;
      }

      function DevilOrItemRoom(f1) {
        if (random(3) != 0) {
          _root.RegularDropPool.push(f1);
        } else {
          _root.DevilRoom.push(f1);
        }
      }

      function FillItemPools() {
        _root.TrinketPool = [30, 31, 32, 33, 34, 36, 37, 38, 39, 40, 41, 43, 44, 45, 46, 48, 51, 53];
        if (_root.SecretUnlocked[68]) {
          _root.TrinketPool.push(35);
        }
        if (_root.SecretUnlocked[74]) {
          _root.TrinketPool.push(47);
        }
        if (_root.SecretUnlocked[72]) {
          _root.TrinketPool.push(49);
        }
        if (_root.SecretUnlocked[77]) {
          _root.TrinketPool.push(50);
        }
        if (_root.SecretUnlocked[78]) {
          _root.TrinketPool.push(42);
        }
        if (_root.SecretUnlocked[81]) {
          _root.TrinketPool.push(29);
        }
        if (_root.SecretUnlocked[84]) {
        }
        if (_root.SecretUnlocked[91]) {
          _root.TrinketPool.push(54);
        }
        if (_root.SecretUnlocked[92]) {
          _root.TrinketPool.push(55);
        }
        if (_root.SecretUnlocked[93]) {
          _root.TrinketPool.push(56);
        }
        if (_root.SecretUnlocked[94]) {
          _root.TrinketPool.push(57);
        }
        if (_root.SecretUnlocked[95]) {
          _root.TrinketPool.push(58);
        }
        if (_root.SecretUnlocked[96]) {
          _root.TrinketPool.push(59);
        }
        if (_root.SecretUnlocked[97]) {
          _root.TrinketPool.push(60);
        }
        if (_root.SecretUnlocked[98]) {
          _root.TrinketPool.push(61);
        }
        _root.RegularDropPool = [1, 1, 2, 3, 4, 5, 6, 7, 8, 8, 10, 12, 13, 14, 15, 19, 19, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 37, 38, 39, 40, 41, 44, 47, 48, 49, 50, 51, 53, 54, 55, 56, 57, 58, 59, 60, 62, 65, 66, 67, 69, 70, 71, 72, 75, 76, 77, 85, 115, 120, 121, 124, 125, 128, 129];
        _root.RegularDropPool.push(136, 137, 138, 140, 142, 143, 144, 147, 148, 149, 150, 151, 152, 153, 154, 155, 157, 160, 163, 167, 169, 173, 177, 178, 180, 183, 191, 192);
        _root.BossDrop = [22, 23, 24, 25, 26, 27 + random(2), 29 + random(3), 29 + random(3), 32, 51, 141, 165, 176, 193, 194, 195, 196, 197, 198];
        _root.SecretRoomItem = [11, 16, 42, 77, 161];
        _root.ShopItem = [54, 54, 60, 60, 64, 21, 21, 139, 156, 147, 195];
        _root.GoldChest = [38, 27 + random(2), 29 + random(3), 26, 1, 50];
        _root.DevilRoom = [8, 67, 79, 80, 81, 115, 118, 133, 145, 159];
        _root.ArenaItem = [26, 17, 19, 21, 44, 70, 14, 13];
        _root.Library = [58, 65, 192];
        _root.GodRoom = [7, 33, 101, 146, 142, 173, 182, 184, 185];
        if (random(2) == 0) {
          _root.SecretRoomItem.push(11, 77);
        }
        if (random(2) == 0) {
          _root.GodRoom.push(184);
          _root.ShopItem.push(144);
        } else {
          _root.ShopItem.push(177);
        }
        if (random(2) == 0) {
          _root.GoldChest.push(179);
          _root.SecretRoomItem.push(190);
        }
        if (_root.SecretUnlocked[65]) {
          _root.RegularDropPool.push(166);
        }
        if (_root.SecretUnlocked[66]) {
          _root.RegularDropPool.push(162);
        }
        if (_root.SecretUnlocked[67]) {
          _root.RegularDropPool.push(188);
        }
        if (_root.SecretUnlocked[69]) {
          _root.RegularDropPool.push(172);
        }
        if (_root.SecretUnlocked[70]) {
          _root.RegularDropPool.push(174);
        }
        if (_root.SecretUnlocked[71]) {
          _root.DevilRoom.push(157);
        }
        if (_root.SecretUnlocked[73]) {
          _root.RegularDropPool.push(186);
        }
        if (_root.SecretUnlocked[75]) {
          _root.SecretRoomItem.push(175);
        }
        if (_root.SecretUnlocked[76]) {
          _root.ShopItem.push(164);
        }
        if (_root.SecretUnlocked[79]) {
          _root.DevilRoom.push(134);
        }
        if (_root.SecretUnlocked[80]) {
          _root.SecretRoomItem.push(168);
        }
        if (_root.SecretUnlocked[82]) {
          _root.RegularDropPool.push(189);
        }
        if (_root.SecretUnlocked[83]) {
          _root.RegularDropPool.push(171);
        }
        if (_root.SecretUnlocked[86]) {
          _root.RegularDropPool.push(170);
        }
        if (_root.SecretUnlocked[85]) {
          _root.RegularDropPool.push(187);
        }
        if (random(2) == 0) {
          _root.RegularDropPool.push(17);
        }
        if (random(3) != 0 && _root.SecretUnlocked[48]) {
          if (random(3) == 0) {
            _root.DevilRoom.push(35);
          } else {
            _root.RegularDropPool.push(35);
          }
          _root.Library.push(35);
        }
        if (random(2) == 0) {
          _root.ShopItem.push(116);
        }
        if (random(2) == 0) {
          _root.ShopItem.push(63);
        }
        if (random(5) == 0) {
          _root.DevilRoom.push(68);
        } else {
          _root.RegularDropPool.push(68);
        }
        if (random(3) == 0) {
          _root.DevilRoom.push(82);
        }
        if (random(3) == 0) {
          _root.DevilRoom.push(84);
        } else {
          if (random(2) == 0) {
            _root.SecretRoomItem.push(84);
          }
        }
        if (_root.SecretUnlocked[3] && _root.characterID != 3) {
          if (random(3) == 0) {
            _root.RegularDropPool.push(34);
          } else {
            if (random(2) == 0) {
              _root.SecretRoomItem.push(34);
            } else {
              _root.DevilRoom.push(34);
            }
          }
          _root.Library.push(34);
        }
        if (_root.SecretUnlocked[1]) {
          _root.RegularDropPool.push(45);
        }
        if (_root.SecretUnlocked[2]) {
          if (random(3) != 0) {
            _root.RegularDropPool.push(46);
          } else {
            _root.DevilRoom.push(46);
          }
        }
        if (_root.SecretUnlocked[7]) {
          _root.ShopItem.push(78);
          _root.Library.push(78);
        }
        if (_root.SecretUnlocked[8] && random(3) != 0) {
          _root.SecretRoomItem.push(20);
        }
        if (_root.SecretUnlocked[9] && random(3) != 0) {
          _root.DevilRoom.push(83);
        }
        if (_root.SecretUnlocked[10]) {
          if (random(3) != 0) {
            _root.RegularDropPool.push(74);
          } else {
            _root.DevilRoom.push(74);
          }
        }
        if (_root.SecretUnlocked[11]) {
          _root.RegularDropPool.push(52);
        }
        if (_root.SecretUnlocked[12]) {
          _root.RegularDropPool.push(36);
        }
        if (_root.SecretUnlocked[13]) {
          _root.SecretRoomItem.push(89);
        }
        if (_root.SecretUnlocked[14]) {
          _root.RegularDropPool.push(91);
        }
        if (_root.SecretUnlocked[18]) {
        }
        if (_root.SecretUnlocked[19]) {
          _root.RegularDropPool.push(86);
        }
        if (_root.SecretUnlocked[20]) {
          _root.RegularDropPool.push(87);
        }
        if (_root.SecretUnlocked[21]) {
          _root.RegularDropPool.push(88);
        }
        if (_root.SecretUnlocked[25] && random(3) != 0) {
          _root.BossDrop.push(92);
        }
        if (_root.SecretUnlocked[26]) {
          _root.RegularDropPool.push(98);
          _root.GodRoom.push(98);
        }
        if (_root.SecretUnlocked[27]) {
          _root.RegularDropPool.push(94);
        }
        if (_root.SecretUnlocked[28]) {
          _root.RegularDropPool.push(95);
        }
        if (_root.SecretUnlocked[33]) {
          _root.RegularDropPool.push(93);
        }
        if (_root.SecretUnlocked[29]) {
          if (random(3) != 0) {
            _root.RegularDropPool.push(97);
          } else {
            _root.DevilRoom.push(97);
          }
          _root.Library.push(97);
        }
        if (_root.SecretUnlocked[30]) {
          _root.RegularDropPool.push(99);
        }
        if (_root.SecretUnlocked[31]) {
          _root.RegularDropPool.push(100);
        }
        if (_root.SecretUnlocked[32]) {
          _root.RegularDropPool.push(96);
        }
        if (_root.SecretUnlocked[34]) {
          _root.RegularDropPool.push(101);
        }
        if (_root.SecretUnlocked[36]) {
          _root.RegularDropPool.push(102);
        }
        if (_root.SecretUnlocked[37]) {
          if (random(3) != 0) {
            _root.RegularDropPool.push(103);
          } else {
            _root.DevilRoom.push(103);
          }
        }
        if (_root.SecretUnlocked[40]) {
          if (random(3) != 0) {
            _root.RegularDropPool.push(104);
          } else {
            _root.DevilRoom.push(104);
          }
        }
        if (_root.SecretUnlocked[38]) {
          _root.RegularDropPool.push(105);
        }
        if (_root.SecretUnlocked[35]) {
          _root.RegularDropPool.push(106);
        }
        if (_root.SecretUnlocked[39]) {
          _root.RegularDropPool.push(107);
        }
        if (_root.SecretUnlocked[43]) {
          _root.RegularDropPool.push(108);
        }
        if (_root.SecretUnlocked[44]) {
          if (random(3) != 0) {
            _root.RegularDropPool.push(109);
          } else {
            _root.DevilRoom.push(109);
          }
        }
        if (_root.SecretUnlocked[47]) {
          _root.RegularDropPool.push(110);
        }
        if (_root.SecretUnlocked[46]) {
          _root.RegularDropPool.push(111);
        }
        if (_root.SecretUnlocked[55]) {
          DevilOrItemRoom(114);
        }
        if (_root.SecretUnlocked[56]) {
          _root.RegularDropPool.push(117);
        }
        if (_root.SecretUnlocked[57]) {
          DevilOrItemRoom(122);
        }
        if (_root.SecretUnlocked[58]) {
          DevilOrItemRoom(126);
        }
        if (_root.SecretUnlocked[59]) {
          _root.RegularDropPool.push(112);
          _root.GodRoom.push(112);
        }
        if (_root.SecretUnlocked[60]) {
          _root.RegularDropPool.push(131);
        }
        if (_root.SecretUnlocked[61]) {
          DevilOrItemRoom(113);
        }
        if (_root.SecretUnlocked[62]) {
          DevilOrItemRoom(127);
        }
        if (_root.SecretUnlocked[63]) {
          DevilOrItemRoom(123);
          _root.Library.push(123);
        }
        for (z in _root.BossDrop) {
          i = 0;
          while (i < _root.RegularDropPool.length) {
            if (_root.BossDrop[z] == _root.RegularDropPool[i]) {
              _root.RegularDropPool.splice(i, 1);
              break;
            }
            ++i;
          }
        }
        for (z in _root.ShopItem) {
          i = 0;
          while (i < _root.RegularDropPool.length) {
            if (_root.ShopItem[z] == _root.RegularDropPool[i]) {
              _root.RegularDropPool.splice(i, 1);
              break;
            }
            ++i;
          }
        }
        for (z in _root.GoldChest) {
          i = 0;
          while (i < _root.RegularDropPool.length) {
            if (_root.GoldChest[z] == _root.RegularDropPool[i]) {
              _root.RegularDropPool.splice(i, 1);
              break;
            }
            ++i;
          }
        }
      }

      function replacePillColor(f2) {
        if (random(2) == 0) {
          _root.pillColors[random(6)] = f2;
        }
      }

      function newstats() {
        _root.pillColors = [1, 2, 3, 4, 5, 6];
        replacePillColor(101);
        replacePillColor(102);
        replacePillColor(103);
        _root.darky(120);
        _root.door = undefined;
        _root.playerTint = [1, 1, 1];
        _root.pillfirst = true;
        _root.bombnext = false;
        _root.notchedAxe = false;
        _root.lastGreedFloor = 0;
        _root.armor = 0;
        _root.pillItem = undefined;
        _root.trinketSlot1 = undefined;
        _root.trinketslot2 = undefined;
        _root.charmOfTheVampire = 0;
        _root.monbb = 0;
        if (_root.floorNum > 2) {
          _root.fade = true;
        }
        _root.floorNum = 1;
        _root.horsedown = 0;
        _root.spacebarItem = 0;
        _root.faceMode = 1;
        _root.headMode = 1;
        _root.bodyMode = 1;
        _root.demonz = 0;
        _root.carryingBook = false;
        _root.hatmode = [1, 1, 1, 1, 1];
        _root.noDice = false;
        _root.hat = [];
        if (_root.characterID > 0 && _root.characterID < 4) {
          hat(_root.characterID + 9);
          _root.classit = true;
        }
        _root.keys = 0;
        _root.bombs = 0;
        _root.coins = 0;
        _root.minibossPool = [0, 1, 2, 3, 5, 6];
        _root.sk = _root.characterID + 1;
        switch (_root.characterID) {
          case 0:
            ++_root.bombs;
            break;
          case 1:
            _root.sk = 3;
            break;
          case 2:
            _root.sk = 2;
            ++_root.keys;
            break;
          case 3:
            _root.sk = 4;
            _root.coins += 3;
            break;
          case 4:
            _root.sk = 5;
            hat(31);
            _root.classit = true;
            break;
          case 5:
            _root.sk = 6;
            hat(37);
            _root.classit = true;
            break;
          case 6:
            _root.sk = 8;
            hat(40);
            _root.classit = true;
            _root.armor = 1;
        }
        _root.hp = 1000;
        _root.upgradeCounter = 0;
        _root.collectionScreen = [];
        _root.colit = 0;
        _root.pillEffects = [];
        _root.krampusFought = false;
        _root.nohead = false;
        _root.nodmg = true;
        _root.devilDeals = 0;
        _root.fireRate = 10;
        _root.tearRange = 23;
        _root.blueFlies = 0;
        _root.luck = 0;
        if (_root.challenge == 2) {
          _root.luck = -2;
        }
        _root.altb3 = false;
        if (_root.characterID == 2) { //These changes get overridden later.
          _root.tearRange -= 5;
        }
        if (_root.characterID == 2) {
          _root.tearRange -= 5;		  //cool, redundancy
          _root.fireRate -= 2;
        }
        var v2 = [0, 0, 0.2, 0.35, 0.05, -0.25, 0];
        v1 = 1 + v2[_root.characterID];
        _root.tearDamage = 3.5 * v1;
        _root.pickedUp = [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0];
        _root.treasuresSkipped = 0;
        _root.catlives = 0;
        _root.fakePennyDrop = false;
        _root.ultraPride = false;
        FillItemPools();
      }

      function ender() {
        var v1 = random(endrooms.length);
        f2 = endrooms[v1];
        endrooms.splice(v1, 1);
        return f2;
      }

      function nch(f5) {
        if (_root.levz[f5]) {		//Is this room valid?
          f12 = true;
        } else {
          f12 = 2;
          f4 = false;
        }
        if (f5 == _root.bossRoom or f5 == _root.bossRoom2 or f5 == _root.secretRoom2) {
          f12 = false;
          f4 = false;
        }
        if (f12 && f12 != 2) {
          for (z in endrooms) {
            if (endrooms[z] == f5) {
              f12 = false;
            }
          }
        }
        if (f5 == _root.secretRoom) {
          f12 = false;
          f4 = false;
        }
        return f12;
      }

      function ncheck1(f5) {
        return nch(f5 + 1) && nch(f5 - 1) && nch(f5 + 10) && nch(f5 - 10);
      }

      function isValidRoom(f1) {
        if (_root.levz[f1] > 0) {
          return 1;
        } else {
          return 0;
        }
      }

      function ncheck(f5) {
        return isValidRoom(f5 + 1) + isValidRoom(f5 - 1) + isValidRoom(f5 + 10) + isValidRoom(f5 - 10);
      }

      function bosschoose() {
        if (_root.floorNum % 2 == 0) {
          _root.altb3 = true;
        }
        if (_root.floorNum % 2 == 1) {
          _root.canSpawnHorseman = _root.SecretUnlocked[5];
          _root.altb = true;
          _root.altb2 = _root.floorNum < 4;
          _root.switchero = _root.floorNum < 4 && random(2);
          _root.swww = _root.floorNum + 1;
        }
        f1 = 'b' + Math.min(8, _root.floorNum) + '-' + random(5);
        _root.bossID = _root.floorNum;
        _root.spawnHorseman = false;
        _root.altboss = false;
        altBosses = [0, 34, 37, 29, 26, 30 + random(2) * 5, 30, 31, 8];
        if (_root.floorNum != 6 && _root.floorNum != 8) {
          if (_root.floorNum == 11) {	
            _root.bossID = 40;
          } else {
            if (_root.bossID > 25) {
            } else {
              if (_root.floorNum > 8) {
                _root.floorNum = 9;
                if (_root.altchap) {
                  _root.bossID = 39;
                } else {
                  _root.bossID = 24;
                  f1 = 'stan';
                }
              } else {
                if (_root.canSpawnHorseman && random(5) == 0) {
                  _root.spawnHorseman = true;
                  _root.canSpawnHorseman = false;
                  f1 = Math.round(_root.floorNum / 2);
                  _root.bossID = f1 + 8;
                  if (random(10) == 0) {
                    f1 = 5;
                    _root.bossID = 22;
                  }
                  f1 = 'h' + f1;
                } else {
                  if (_root.SecretUnlocked[88] && _root.floorNum == 7 && random(3) == 0) {
                    if (random(2) == 0) {
                      _root.bossID = 38;
                    } else {
                      _root.bossID = 41;
                    }
                  } else {
                    if (_root.demonz == 1 && random(10) == 0) {
                      _root.demonz = 2;
                      _root.bossID = 23;
                      f1 = 'demon';
                    } else {
                      if (_root.floorNum == 7 && random(3) == 0) {
                        f1 = [30, 33];
                        _root.bossID = f1[random(f1.length)];
                      } else {
                        if (_root.altb3 && _root.altchap && random(4) == 0 && _root.floorNum < 6) {
                          _root.altb3 = false;
                          f1 = Math.round(_root.floorNum / 2 - 1.5);
                          if (random(2) == 0) {
                            f2 = [28, 36];
                          } else {
                            f2 = [32, 27];
                          }
                          _root.bossID = f2[f1];
                        } else {
                          if (_root.altb && random(5) == 0) {
                            _root.altb = false;
                            f1 = Math.round(_root.floorNum / 2);
                            _root.bossID = f1 + 12;
                            f1 = 'a' + f1 + '-' + random(3);
                            if (_root.altchap && _root.floorNum == 1) {
                            }
                          } else {
                            if (_root.altb2 && random(4) == 0 && (_root.chap > 2 or !_root.altchap)) {
                              _root.altb2 = false;
                              f1 = Math.round(_root.floorNum / 2) + 4;
                              _root.bossID = f1 + 12;
                              f1 = 'a' + f1 + '-' + random(3);
                            } else {
                              if (_root.switchero) {
                                f1 = _root.swww;
                                _root.bossID = f1;
                                if (_root.altchap) {
                                  _root.bossID = altBosses[_root.bossID];
                                }
                                f1 = 'b' + Math.min(8, f1) + '-' + random(5);
                              } else {
                                _root.bossID = _root.floorNum;
                                if (_root.altchap) {
                                  _root.bossID = altBosses[_root.bossID];
                                }
                                f1 = 'b' + Math.min(8, _root.bossID) + '-' + random(5);
                              }
                            }
                          }
                        }
                      }
                    }
                  }
                }
              }
            }
          }
        }
        if (_root.bossID > 25) {
          f6 = [26, 27, 29, 30, 31, 32, 33, 36, 37, 38, 40, 42];
          f7 = [2, 3, 13, 14, 15, 17, 18, 34, 7, 11, 39, 41];
          f1 = 'b' + _root.bossID + '-' + random(4);
          for (e in f6) {
            if (_root.bossID == f6[e]) {
              _root.altboss = true;
              if (_root.bossID == 32 or _root.bossID == 27) {
                _root.altboss = 2;
              }
              if (_root.bossID == 38) {
                f1 = 'h3';
              }
            }
          }
        }
        if (random(2) == 0) {
          if (_root.bossID == 17 && _root.SecretUnlocked[22] or _root.bossID == 3 && _root.SecretUnlocked[23] or _root.bossID == 5 && _root.SecretUnlocked[24] or _root.bossID == 41 && _root.SecretUnlocked[89]) {
            _root.altboss = true;
            switch (_root.bossID) {
              case 17:
                _root.bossID = 20;
                break;
              case 3:
                _root.bossID = 21;
                break;
              case 5:
                _root.bossID = 19;
                break;
              case 41:
                _root.bossID = 42;
            }
          }
        }
        if (_root.bossID == 8 && _root.SecretUnlocked[45]) {
          _root.bossID = 25;
        }
        _root.swww = _root.floorNum;
      }

      function checkTreasureSkip() {
        if (_root.beenlev[_root.boner] != 2 && _root.floorNum != 1 && _root.boner != undefined) {
          ++_root.treasuresSkipped;
        }
        if (_root.beenlev[_root.boner2] != 2 && _root.labyrinthCurse && _root.floorNum != 1 && _root.boner2 != undefined) {
          ++_root.treasuresSkipped;
        }
      }

      function revealSecretRoom() {
        if (!_root.foundSecretRoom) {
          _root.mmus = _root.soundy('secret room find.mp', 100);
          _root.foundSecretRoom = true;
        }
      }

      function revealSecretRoom2() {
        if (!_root.foundSecretRoom2) {
          _root.mmus = _root.soundy('isaacxpsecretroomreveal2.mp3', 100);
          _root.foundSecretRoom2 = true;
        }
      }

      function itmc() {
        if (_root.levcol[e] > 0) {
          mpiece.itmc.gotoAndStop(_root.levcol[e]);
        } else {
          mpiece.itmc.gotoAndStop('empty');
        }
      }

      function mapd() {
        qq = _root._quality;
        if (qq != 'high') {
          _root._quality = 'high';
        }
        _root.map.fillRect(_root.map.rectangle, 0);
        maxxx = undefined;
        if (satan or error or _root.darknessCurse) {
          e = 35;
          f1 = (e % 10) * 25 + 15;
          f2 = Math.round(e / 10 - 0.5) * 10 + 7;
          maxx = new flash.geom.Matrix();
          maxx.translate(f1, f2);
          maxx.scale(_root._xscale / 100, _root._yscale / 100);
          mpiece.gotoAndStop(7);
          _root.map.draw(mpiece, maxx);
          minx = f1;
          maxxx = f1;
          miny = f2;
          maxy = f2;
        } else {
          for (e in _root.levz) {
            if (e < 110) {
              if (_root.levz[e] != 0 && (_root.seenRoom[e] or haveEffect[54]) && (_root.secretRoom != e && _root.secretRoom2 != e or _root.beenlev[e] && (e != _root.arenaRoom or _root.arenaActive))) {
                maxx = new flash.geom.Matrix();
                f1 = (e % 10) * 25 + 15;
                f2 = Math.round(e / 10 - 0.5) * 10 + 7;
                if (f1 > 0) {
                  if (maxxx == undefined) {
                    maxxx = f1;
                    minx = maxxx;
                    maxy = f2;
                    miny = maxy;
                  } else {
                    minx = Math.min(f1, minx);
                    maxxx = Math.max(f1, maxxx);
                    miny = Math.min(f2, miny);
                    maxy = Math.max(f2, maxy);
                  }
                  maxx.translate(f1, f2);
                  if (_root.lev == e) {
                    mpiece.gotoAndStop(3);
                  } else {
                    if (_root.beenlev[e]) {
                      mpiece.gotoAndStop(2);
                    } else {
                      mpiece.gotoAndStop(1);
                    }
                  }
                  itmc();
                  maxx.scale(_root._xscale / 100, _root._yscale / 100);
                  _root.map.draw(mpiece, maxx);
                }
              }
            }
          }
          e = 0;
          while (e < _root.levz.length) {
            if (_root.levz[e] != 0 && e < 110) {
              maxx = new flash.geom.Matrix();
              f1 = (e % 10) * 25 + 15;
              f2 = Math.round(e / 10 - 0.5) * 10 + 7;
              maxx.translate(f1, f2);
              maxx.scale(_root._xscale / 100, _root._yscale / 100);
              mpiece.gotoAndStop(1);
              if (_root.shopl == e && (_root.shopaz or haveEffect[21])) {
                mpiece.gotoAndStop(4);
              } else {
                if (_root.boner == e && (haveEffect[21] or _root.treasd) or _root.boner2 == e && (haveEffect[21] or _root.treasd2)) {
                  mpiece.gotoAndStop(5);
                } else {
                  if ((_root.bossRoom == e && (!_root.labyrinthCurse or _root.bossID == _root.bossID2) or _root.bossRoom2 == e && _root.bossID != _root.bossID2) && (haveEffect[21] or _root.bossd)) {
                    mpiece.gotoAndStop(6);
                  } else {
                    if (_root.secretRoom == e && (haveEffect[54] or _root.foundSecretRoom)) {
                      mpiece.gotoAndStop(7);
                    } else {
                      if (_root.secretRoom2 == e && _root.foundSecretRoom2) {
                        mpiece.gotoAndStop(16);
                      } else {
                        if (_root.minibossRoom == e && (haveEffect[21] or _root.minibossKnown)) {
                          mpiece.gotoAndStop(8);
                        } else {
                          if (_root.arcadeRoom == e && (haveEffect[21] or _root.seenArcade)) {
                            mpiece.gotoAndStop(9);
                          } else {
                            if (_root.curseRoom == e && (haveEffect[21] or _root.seenCurseRoom)) {
                              mpiece.gotoAndStop(14);
                            } else {
                              if (_root.arenaRoom == e && (haveEffect[21] or _root.chambb)) {
                                if (_root.bossArena) {
                                  mpiece.gotoAndStop(11);
                                } else {
                                  mpiece.gotoAndStop(10);
                                }
                              } else {
                                if (_root.libraryRoom == e && (haveEffect[21] or _root.librarySeen)) {
                                  mpiece.gotoAndStop(12);
                                } else {
                                  if (_root.sacrificeRoom == e && (haveEffect[21] or _root.sacRoomRevealed)) {
                                    mpiece.gotoAndStop(13);
                                  }
                                }
                              }
                            }
                          }
                        }
                      }
                    }
                  }
                }
              }
              if (mpiece._currentframe > 1) {
                itmc();
                _root.map.draw(mpiece, maxx);
                minx = Math.min(f1, minx);
                maxxx = Math.max(f1, maxxx);
                miny = Math.min(f2, miny);
                maxy = Math.max(f2, maxy);
              }
            }
            ++e;
          }
        }
        _root.mapa._yscale = 10000 / _root._xscale;
        _root.mapa._xscale = _root.mapa._yscale;
        _root.mapa._x = 130 - (maxxx + minx) / 2;
        _root.mapa._y = 40 - (maxy + miny) / 2;
        if (qq != 'high') {
          _root._quality = qq;
        }
      }

      function outgrid(f1) {
        var v1 = f1 % rowz;
        var v2 = Math.round(f1 / rowz - 0.5);
        xenf = v1 * roxx;
        yenf = v2 * roxx;
      }

      function ingrid(f1, f2, f3) {
        if (f3) {
          f1 = Math.min(560, Math.max(80, f1));
          f2 = Math.min(400, Math.max(160, f2));
          f1 /= roxx;
          f2 /= roxx;
          f1 = Math.round(f1);
          f2 = Math.round(f2);
          f1 = Math.max(0, Math.min(rowz - 1, f1));
          f2 = Math.max(0, f2);
          return f1 + rowz * f2;
        }
        f1 = Math.min(620, Math.max(20, f1));
        f2 = Math.min(447, Math.max(110, f2));
        f1 /= roxx;
        f2 /= roxx;
        f1 = Math.round(f1);
        f2 = Math.round(f2);
        f1 = Math.max(0, Math.min(rowz - 1, f1));
        f2 = Math.max(0, f2);
        return f1 + rowz * f2;
      }

      function gridp(f1, f2, f3, f4) {
        f1 -= gridx;
        f2 -= gridy;
        if (f3 == undefined) {
          return [int(f1 / gridv + 1) * gridmax + 1, int(f2 / gridv) + 1];
        } else {
          return [int(f1 / gridv + 1 + f3) * gridmax + 1, int(f2 / gridv + f4) + 1];
        }
      }

      function gridput(f5, f6) {
        a = 0;
        for (;;) {
          if (!(grid.getPixel(f5[0], f5[1]) != 0 && a < gridmax)) break;
          ++f5[0];
          ++a;
        }
        grid.setPixel(f5[0], f5[1], f6);
      }

      function gridput2(f5, f6) {
        a = 0;
        for (;;) {
          if (!(grid2.getPixel(f5[0], f5[1]) != 0 && a < gridmax)) break;
          ++f5[0];
          ++a;
        }
        grid2.setPixel(f5[0], f5[1], f6);
      }

      function topz(cap) {
        timer[cap] = getTimer();
      }

      function tip(cap) {
        alltimer[cap] += (getTimer() - timer[cap]) / 25;
      }

      function crand(f1) {
        if (cra1 == undefined) {
          cra1 = Math.random() * Math.PI * 2;
          cra2 = f1;
          return Math.cos(cra1) * f1;
        } else {
          f1 = cra1;
          cra1 = undefined;
          return Math.sin(f1) * cra2;
        }
      }

      function notUpgrade(f1) {
        var v2 = f1 != 115 && f1 != 138 && f1 != 143 && f1 != 146 && f1 != 149 && f1 != 150 && f1 != 151 && f1 != 152 && f1 != 154 && f1 != 157 && f1 != 168 && f1 != 170 && f1 != 179 && f1 != 180 && f1 != 182 && f1 != 183 && f1 != 184 && f1 != 185 && f1 != 187 && f1 != 189 && f1 != 190 && f1 != 191 && f1 != 197;
        return f1 > 8 && f1 != 12 && f1 != 16 && f1 != 48 && f1 != 50 && f1 != 51 && f1 != 55 && f1 != 57 && f1 != 52 && f1 != 59 && f1 != 67 && f1 != 68 && f1 != 70 && f1 != 87 && f1 != 89 && f1 != 88 && f1 != 90 && f1 != 92 && f1 != 95 && f1 != 99 && f1 != 100 && f1 != 101 && f1 != 103 && f1 != 104 && f1 != 108 && f1 != 109 && f1 != 110 && v2;
      }

      function keepItem(f1) {
        if ((f1 == 79 or f1 == 80 or f1 == 82 or f1 == 83 or f1 == 81 or f1 == 113 or f1 == 122 or f1 == 118 or f1 == 157 or f1 == 159 or f1 == 145) && satan && !haveTrinket(56)) {
          _root.trg.d.d.gotoAndStop(10);
        } else {
          if (satan && _root.trg.d.d._currentframe == 10) {
            _root.trg.d.d.gotoAndStop(9);
          }
        }
        if (_root.characterID == 4 && satan) {
          _root.trg.d.d.gotoAndStop(11);
        }
        var Familiars = [8, 67, 95, 99, 100, 113, 163, 167, 174, 188];
        var isFamiliar = false;
        for (o in Familiars) {
          if (Familiars[o] == f1) {
            isFamiliar = true;
          }
        }
        var numFamiliars = 0;
        if (isFamiliar) {
          for (o in Familiars) {
            numFumiliars += _root.pickedUp[Familiars[o]]; //Count the number of familiars you have from the above pool.
          }
        }
        if (isFamiliar && numFamiliars > 2) {
          return 0; //Game throws out familiars if you have more than 2 from the above pool.
        } else {
          if (_root.pickedUp[f1] or _root.collectedItem[f1] && random(5) == 0) {
            return 0; //Game throws out items you've picked up....or old items 20% of the time.
          } else {
            if (notUpgrade(f1)) {
              return f1;
            } else {
              if (1 / (1.2 + _root.upgradeCounter * 3) > Math.random()) {
                return f1;
              } else {
                return 0;
              }
            }
          }
        }
      }

      function GenerateItem() {
        var itemID = 0;
        var tries = 0;
        while (itemID == 0) {								//This function should literally never return 0! But sometimes it SOMEHOW DOES.
          ++tries;
          if (tries > 100) {								//AGH We couldn't drop an item what do we do?
            var v3 = random(_root.RegularDropPool.length);	//Well, let's just get a random treasure period.
            itemID = keepItem(_root.RegularDropPool[v3]);		//First checking if we shouldn't throw that one out too.
            if (itemID > 0) {								//If it's valid, let's drop it.
              _root.RegularDropPool.splice(v3, 1);			//And remove it as per usual.
            }												//
            if (_root.RegularDropPool.length <= 5) {		//If the regular item pool is looking slim...
              FillItemPools();								//REFRESH ALL THE ITEM POOLS.
            }
          } else {
            if (_root.lev == _root.libraryRoom) {
              var v3 = random(_root.Library.length);
              itemID = keepItem(_root.Library[v3]);
              if (itemID > 0) {
                if (lib == v3) {							//I literally have no idea what this does.
                  itemID = -1;								//None whatsoever.
                  lib = v3;									//If the if statement were true wouldn't this already be the ca-screw it I don't even know.
                }
              }
            } else {
              if (_root.ArenaItem.length > 0 && _root.lev == _root.arenaRoom && !_root.bossArena) {
                var v3 = random(_root.ArenaItem.length);
                itemID = keepItem(_root.ArenaItem[v3]);
                if (itemID > 0) {
                  _root.ArenaItem.splice(v3, 1);
                }
              } else {
                if (_root.DevilRoom.length > 0 && (satan or beggar == 2 or _root.lev == _root.curseRoom)) {
                  beggar = false;
                  if (_root.godRoomFloor) {
                    var v3 = random(_root.GodRoom.length);
                    itemID = keepItem(_root.GodRoom[v3]);
                  } else {
                    var v3 = random(_root.DevilRoom.length);
                    itemID = keepItem(_root.DevilRoom[v3]);
                    if (itemID > 0) {
                      _root.DevilRoom.splice(v3, 1);
                    }
                  }
                } else {
                  if (_root.GoldChest.length > 0 && treas && _root.floorNum != 11) {
                    var v3 = random(_root.GoldChest.length);
                    itemID = keepItem(_root.GoldChest[v3]);
                    if (itemID > 0) {
                      _root.GoldChest.splice(v3, 1);
                    }
                  } else {
                    if ((_root.lev == _root.shopl or beggar) && _root.ShopItem.length > 1) {
                      beggar = false;
                      var v3 = random(_root.ShopItem.length);
                      itemID = keepItem(_root.ShopItem[v3]);
                      if (itemID > 0) {
                        _root.ShopItem.splice(v3, 1);
                      }
                    } else {
                      if ((_root.lev == _root.boner or _root.lev == _root.boner2) && random(2) == 0 && _root.UnknownPool.length > 1) {
                        var v3 = random(_root.UnknownPool.length);
                        itemID = keepItem(_root.UnknownPool[v3]);
                        if (itemID > 0) {
                          _root.UnknownPool.splice(v3, 1);
                        }
                      } else {
                        if (_root.lev == _root.secretRoom) {
                          var v3 = random(_root.SecretRoomItem.length);
                          itemID = keepItem(_root.SecretRoomItem[v3]);
                          if (itemID > 0) {
                            _root.SecretRoomItem.splice(v3, 1);
                          }
                        } else {
                          if (_root.lev == _root.arenaRoom && _root.bossArena) {
                            var v3 = random(_root.BossDrop.length);
                            itemID = keepItem(_root.BossDrop[v3]);
                            if (itemID > 0) {
                              _root.BossDrop.splice(v3, 1);
                            }
                          } else {
                            if (_root.lev == _root.bossRoom or _root.lev == _root.bossRoom2) {
                              if (_root.bossID == 23 && _root.DevilRoom.length > 0) {
                                e = 0;
                                while (e < 100) {
                                  var v3 = _root.DevilRoom[random(_root.DevilRoom.length)];
                                  if (!haveEffect[v3]) {
                                    itemID = v3;
                                    e = 1000;
                                  }
                                  ++e;
                                }
                              } else {
                                if (_root.bossID == 38 && !haveEffect[181]) {
                                  itemID = 181;
                                } else {
                                  if (_root.bossID == 22 && !haveEffect[130]) {
                                    _root.SecretUnlocked[32] = true;
                                    itemID = 130;
                                  } else {
                                    if (_root.bossID == 21 && !haveEffect[96]) {
                                      _root.SecretUnlocked[32] = true;
                                      itemID = 96;
                                    } else {
                                      if (_root.bossID == 19 && !haveEffect[99]) {
                                        _root.SecretUnlocked[30] = true;
                                        itemID = 99;
                                      } else {
                                        if (_root.bossID == 20 && (!haveEffect[100] or !haveEffect[50])) {
                                          _root.SecretUnlocked[31] = true;
                                          if (haveEffect[100] or random(6) == 0) {
                                            itemID = 50;
                                          } else {
                                            itemID = 100;
                                          }
                                        } else {
                                          if (_root.bossID > 8 && _root.bossID < 13) {
                                            _root.SecretUnlocked[7] = true;
                                            itemID = 73;
                                          } else {
                                            var v3 = random(_root.BossDrop.length);
                                            itemID = keepItem(_root.BossDrop[v3]);
                                            if (itemID > 0) {
                                              _root.BossDrop.splice(v3, 1);
                                            }
                                          }
                                        }
                                      }
                                    }
                                  }
                                }
                              }
                            } else {
                              var v3 = random(_root.RegularDropPool.length);
                              itemID = keepItem(_root.RegularDropPool[v3]);
                              if (itemID > 0) {
                                _root.RegularDropPool.splice(v3, 1);
                              }
                            }
                          }
                        }
                      }
                    }
                  }
                }
              }
            }
          }
        }
        return itemID;
      }

      function specialColoring(trg) {
        trg.uncol = 200 + fra;
        if (pacman) {
          trg.uncol = unic + fra + 1;
          colorit(trg, 0.3, 0.5, 1.2, 0, 0, 0);
        } else {
          if (trg.frezz > 0) {
            colorit(trg, 0.22, 0.22, 0.22, 40, 40, 40);
            trg.uncol = trg.frezz + fra + 2;
          } else {
            if (trg.poisonDuration > 0 && trg.s != 64 && trg.s != 46) {
              f1 = Math.max(0.6, (200 - trg.poisonDuration) / 200 - 0.1);
              colorit(trg, f1, 1, f1, 0, (1 - f1) * 90, 0);
            } else {
              if (trg.alter == 2 && trg.s == 42) {
                colorit(trg, 0.66, 1, 0.74, 0, 0, 0);
              } else {
                if (trg.champion or trg.specozz) {
                  if (trg.specol == undefined) {
                    trg.specol = random(specol.length);
                  }
                  var f1 = trg.specol;
                  colorit(trg, specol[f1][0], specol[f1][1], specol[f1][2], 0, 0, 0);
                } else {
                  if (trg.spid > 0) {
                    if (trg.spida == 2) {
                      colorit(trg, 0.5, 0.5, 0.5, -100, -100, -100);
                    } else {
                      colorit(trg, 0.5, 0.5, 0.5, 150, 150, 150);
                    }
                    trg.uncol = fra + 10;
                  } else {
                    if (trg.specoz) {
                      var f1 = trg.specoz;
                      if (specol2[f1].length > 4) {
                        colorit(trg, specol2[f1][0], specol2[f1][1], specol2[f1][2], specol2[f1][3], specol2[f1][4], specol2[f1][5]);
                      } else {
                        colorit(trg, specol2[f1][0], specol2[f1][1], specol2[f1][2], 0, 0, 0);
                      }
                    } else {
                      colorit(trg, 1, 1, 1, 0, 0, 0);
                    }
                  }
                }
              }
            }
          }
        }
      }

      function momlo() {
        if (trrisss + 45 + random(120) <= fra) {
          trrisss = fra;
          _root.soundy('Mom_Vox_Isaac_' + random(3) + '.mp');
        }
        mome = random(4);
        if (mome >= 2) {
          ++mome;
        }
        moml = fra + 30;
        mom[mome].d.gotoAndStop(2);
      }

      function atta(f7) {
        return (f7 >= 7 or f7 <= 2 or f7 == 4 or f7 == 5 or f7 == 3) && f7 != 37 && f7 != 33;
      }

      function trgdy(f1) {
        if (f1) {
          var v1 = Math.max(0, 8.5 + trg.dy);
          trg.d._y = trg.dy * 0.5 - 15 + v1 * v1;
          if (trg.ba) {
            trg.d._y += 5;
          }
        } else {
          trg.d._y = trg.dy;
        }
        if (trg.d._xscale == 100) {
          trg.d.sh._y = -trg.d._y;
        } else {
          trg.d.sh._y = (-trg.d._y / trg.d._xscale) * 100;
        }
      }

      function attach(trg, f7) {
        if (atta(f7)) {
          trg.gotoAndStop(1);
          if (f7 == 72 or f7 == 73) {
            f7 = 71;
          }
          if (f7 == 75 or f7 == 76 or f7 == 77) {
            f7 = 74;
          }
          if (f7 == 7 && _root.floorNum > 6 && _root.floorNum != 9) {
            f7 = 'gibs-red';
          } else {
            f7 = 'b' + f7;
          }
          trg.attachMovie(f7, 'd', 30);
        } else {
          trg.gotoAndStop(f7);
        }
      }

      function abr() {
        if (fra % 2 == 0) {
          return 'A';
        } else {
          return 'B';
        }
      }

      function efly(trg) {
        var v1 = create(trg.xp + 0.2, trg.yp + 0.2, 0, 0, 0, 0, 96);
        v1.efly = true;
        v1.trg2 = trg;
        v1.outway = true;
        v1.wtf = flyer++;
      }

      function create(f1, f2, f3, f4, f5, f6, f7, f9) {
        var v5 = f7;
        ++ballz;
        var v13 = 'b' + ballz;
        var v11 = ball.length;
        var v8 = 0;
        if (v11 == 0) {
          v8 = ballz + 20000;
        } else {
          v8 = ballz + 10000;
        }
        f18 = false;
        if (f7 == 33.1) {
          f7 == 33;
          f18 = true;
          v8 = 323;
        } else {
          if (f7 == 33) {
            v8 = 322;
          }
        }
        f7 = Math.round(f7);
        v5 -= f7;
        var v10 = atta(f7);
        namer2 = 'ball';
        if (f7 == 9) {
          namer2 = 'bullet1';
          v10 = false;
        }
        if (v10) {
          namer2 = 'emptyz';
        }
        ball[v11] = attachMovie(namer2, v13, v8);
        var v2 = ball[v11];
        if (f18) {
          v2.holi = true;
        }
        v2.hp = hps[f7];
        v2.mhp = v2.hp;
        if (f7 == 5 && v5 > 0.04) {
          for (;;) {
            if (!(enfcheckx(f1, f2, 320, 280, 1000) && !enfcheck(f1 * 0.5 + 160, f2, 320, 280, 100))) break;
            posw(f1, f2, 20);
            f1 = xenf;
            f2 = yenf;
          }
        }
        v2.e = ballz;
        v2.xp = f1;
        v2.yp = f2;
        v2.rp = f3;
        v2.ma = masses[f7];
        v2.sss = f9;
        switch (f9) {
          case 42:
            _root.soundy('stoneshoot' + random(3) + '.wav');
            break;
          case 12:
          case 26:
            if (v2.alter != 3) {
              _root.soundy('Shakey_Kid_Roar_' + random(3) + '.mp', 100);
            } else {
            case 19:
            case 31:
            case 30:
            case 14:
            case 11:
            case 34:
            case 62:
            case 79:
            case 88:
            case 86:
            case 90:
            case 99:
            case 98:
            case 92:
            case 100:
            case 102:
              _root.soundy('bloodshoot' + random(3) + '.wav');
              break;
            case 56:
              _root.soundy('meatheadshoot' + fra % 3 + '.wav');
              break;
            case 69:
              _root.soundy('Cute_Grunt_' + random(3) + '.mp', 100);
              break;
            case 63:
            case 64:
            case 65:
            case 66:
              _root.soundy('Monster_Grunt_0_' + abr() + '.mp', 100);
              break;
            case 38:
              _root.soundy('Floaty_Baby_Roar_' + random(3) + '.mp', 85);
            }
        }
        v2.xbew = f4 + Math.random() * 0.01;
        v2.xb = v2.xbew;
        v2.ybew = f5 + Math.random() * 0.01;
        v2.xb = v2.ybew;
        v2.s = f7;
        v2.e = ballz;
        if (v10) {
          attach(v2, Math.round(f7));
        } else {
          v2.gotoAndStop(f7);
          if (v2.holi) {
            v2.gotoAndStop(32);
          }
        }
        v2.sca = 1;
        v2.fra = fra;
        v2.spl = 0;
        v2.bh = true;
        v2.rr = 1;
        if (v2.s == 49) {
          v2.alter = 1;
        }
        v2.apf = v2.s <= 5 or v2.s == 19 or v2.s == 20 or v2.s == 33 or v2.s == 36 or v2.s == 43 or v2.s == 28 or v2.s == 45 or v2.s == 53 or v2.s == 62 or v2.s >= 72 && v2.s <= 77 or v2.s == 78 or v2.s == 84 or v2.s == 101;
        v2.minb = v2.s > 45 && v2.s < 53;
        if (!_root.beenlev2[_root.lev]) {
          if (f7 > 9 && f7 != 13 && f7 != 18 && f7 != 20 && f7 != 28 && f7 != 33 && f7 != 35 && f7 != 36 && f7 != 37 && f7 != 42 && f7 != 19 && f7 != 43 && f7 != 44 && f7 != 45 && fra < 10 && !v2.minb && f7 < 62) {
            v2.champion = random(20) == 0;
          }
        }
        var v9 = v2.minb;
        f2 = f7 == 15 or f7 == 29 or f7 == 61 or f7 == 38 or f7 == 35 or f7 == 88 or f7 == 44 or f7 == 39 or f7 == 57 or f7 == 42 or f7 == 30 or v9;
        f1 = f7 == 41 or f7 == 55 or f7 == 60 or f7 == 53;
        if (v5 && f7 == 28) {
          altboss = 2;
        }
        if (v5 && (f7 == 100 or f7 == 67 or f7 == 68 or f7 == 62 or f7 == 19)) {
          altboss = 1;
        }
        if (f7 == 16 or f7 == 27 or f7 == 25 or f7 == 26 or f7 == 24 or f7 == 14 or f2 or f1) {
          if ((v5 > 0.15 or random(100) == 0) && (f7 == 26 or f7 == 15 or f7 == 30 or f7 == 88 or f7 == 16 or f7 == 39 or f7 == 55)) {
            v2.alter = 3;
            if (f7 == 26 or f7 == 55) {
              efly(v2);
            }
          } else {
            if ((v5 or random(21) == 0 && !f1 or random(25) == 0 && !f2 or random(100) == 0 && !v9) && f7 != 15) {
              if (f7 == 46 && flox.s == 38) { //ultrapride
                flox.minb = 3;
                v2.minb = 3;
                flox.alter = 3;
                v2.alter = 3;
                v2._xscale *= 1.6;
                v2._yscale *= 1.6;
                flox._xscale *= 1.33;
                flox._yscale *= 1.33;
                v2.hp *= 2;
                v2.mhp = v2.hp;
                flox.hp *= 1.5;
                flox.mhp = flox.hp;
              } else {
                v2.alter = 2;
                if (v9) {
                  v2.minb = 2;
                  v2._xscale *= 1.25;
                  v2._yscale *= 1.25;
                  f1 = 1.5;
                  switch (v2.s) { //champion miniboss
                    case 48:
                      f1 = 1.3;
                      break;
                    case 49:
                      f1 = 1.6;
                      break;
                    case 51:
                      v2.specol = 8;
                      v2.specozz = true;
                      specialColoring(v2);
                      f1 = 1;
                      break;
                    case 52:
                      v2.specol = 9;
                      v2.specozz = true;
                      specialColoring(v2);
                      f1 = 1;
                  }
                  v2.hp *= f1;
                  v2.mhp = v2.hp;
                }
              }
            } else {
              v2.alter = 1;
            }
          }
          if ((f7 == 38 or f7 == 14) && v2.alter == 2) {
            v2.hp *= 1.5;
            v2.mhp = v2.hp;
          }
          if (f7 == 57 && v2.alter == 2 or v2.s == 55 && v2.alter == 3) {
            v2.hp *= 1.25;
            v2.mhp = v2.hp;
          }
          if (f7 == 29 && v2.alter == 2) {
            v2.hp *= 1.5;
            v2.mhp = v2.hp;
            v2.wait = 0;
          }
          if (f1 && v2.alter == 2) {
            v2.hp *= 1.25;
            v2.mhp = v2.hp;
            if (_root.floorNum < 9) {
              v2.hallo = true;
            }
          }
        }
        if (f7 == 90) {
          v2.alter = random(4) + 1;
          efly(v2);
        }
        if (f7 == 15 && v2.alter != 3) {
          if (altboss == 2 or v5 > 0.15) {
            v2.alter = 3;
          } else {
            if (altboss or v5) {
              v2.alter = 2;
            } else {
              v2.alter = 1;
            }
          }
        }
        if (f7 == 81) {
          if (v5) {
            v2.alter = 2;
            v2.hp *= 1.1;
            v2.mhp = v2.hp;
            f4 = ['Isaac', 'Magdalena', 'Cain', 'Judas', 'XXX', 'Eve', 'Samson'];
            displayBannerMessage(f4[_root.characterID] + ' vs ' + 'Krampus');
          } else {
            v2.alter = 1;
          }
        }
        f1 = [];
        if (_root.SecretUnlocked[3] or _root.lev % 4 == 0) {
          if (altboss) {
            switch (f7) {
              case 67:
                f1 = [16, 19];
                break;
              case 19:
                if (f155 == undefined) {
                  f155 = random(3) == 0;
                }
                if (!wtfe or spezz) {
                  wtfe = true;
                  f1 = [16, 3];
                  if (f155) {
                    f1 = [21];
                  }
                }
                break;
              case 28:
                if ((!wtfe or spezz) && altboss == 2) {
                  wtfe = true;
                  f1 = [22];
                }
                break;
              case 68:
                f1 = [3];
                break;
              case 62:
                if (!wtfe or spezz) {
                  wtfe = true;
                  f1 = [16];
                }
            }
          } else {
            switch (f7) {
              case 98:
                f1 = [18];
                break;
              case 99:
                f1 = [21, 7];
                break;
              case 100:
                f1 = [18, 20];
                break;
              case 45:
                if (!wtfe or spezz) {
                  wtfe = true;
                  f1 = [19, 7];
                }
                break;
              case 63:
                f1 = [7];
                break;
              case 64:
                f1 = [17];
                break;
              case 65:
                f1 = [16];
                break;
              case 66:
                if (!wtfe or spezz) {
                  wtfe = true;
                  f1 = [18];
                }
                break;
              case 71:
              case 72:
              case 73:
                if (!wtfe or spezz) {
                  wtfe = true;
                  f1 = [15];
                }
                break;
              case 43:
                if (!altboss) {
                  f1 = [14];
                }
                break;
              case 68:
                f1 = [12, 13];
                break;
              case 36:
                f1 = [11];
                break;
              case 28:
                if ((!wtfe or spezz) && !altboss) {
                  wtfe = true;
                  f1 = [8, 9];
                }
                break;
              case 19:
                if (!wtfe or spezz) {
                  wtfe = true;
                  f1 = [3, 7];
                }
                break;
              case 67:
                f1 = [5, 6];
                break;
              case 79:
                if ((i == 0 or spezz) && !altboss) {
                  f1 = [3, 4];
                }
                break;
              case 20:
                f1 = [1, 2];
            }
          }
        }
        if (f1.length > 0 && (fra < 40 or spezz)) {
          if (spezz) {
            if (f1[0] == spezz or f1[1] == spezz) {
              v2.specoz = spezz;
            }
          } else {
            if (_root.SecretUnlocked[42]) {
              f2 = random(5);
            } else {
              f2 = random(10);
            }
            if (f2 <= f1.length) {
              v2.specoz = f1[f2];
              spezz = v2.specoz;
            }
          }
        }
        if (v2.s == 42) {
          specialColoring(v2);
        }
        if (v2.specoz) {
          specialColoring(v2);
          v2.champion = false;
          if (v2.s == 45) {
            if (v2.specoz == 7) {
              v2.mhp *= 0.85;
              v2.hp *= 0.85;
            }
          } else {
            switch (v2.specoz) {
              case 19:
                if (v2.s == 67) {
                  v2._yscale = 80;
                  v2._xscale = 70;
                }
                break;
              case 14:
                v2._yscale = 80;
                v2._xscale = 80;
                break;
              case 12:
                v2._yscale = 85;
                v2._xscale = 85;
                break;
              case 9:
                v2.mhp *= 0.85;
                v2.hp *= 0.85;
                v2._yscale = 85;
                v2._xscale = 85;
                break;
              case 5:
                v2.spl = 30;
                break;
              case 3:
                v2.spl = 30;
                break;
              case 1:
                if (!wtfe) {
                  --i;
                  wtfe = true;
                }
                v2._yscale = 75;
                v2._xscale = 75;
                v2.mhp *= 0.45;
                v2.hp *= 0.45;
                break;
              case 11:
                v2._yscale = 111;
                v2._xscale = 111;
                break;
              case 21:
              case 18:
              case 2:
              case 6:
              case 4:
              case 8:
              case 15:
              case 16:
                if (v2.s != 100) {
                  v2.mhp *= 1.25;
                  v2.hp *= 1.25;
                  if (v2.s == 67) {
                    v2.mhp *= 1.25;
                    v2.hp *= 1.25;
                  }
                  v2._yscale = 115;
                  v2._xscale = 115;
                }
                break;
              case 7:
                if (v2.s == 99) {
                  v2.mhp *= 0.55;
                  v2.hp *= 0.55;
                  v2._yscale = 58;
                  v2._xscale = 58;
                  if (!wtfe) {
                    --i;
                    wtfe = true;
                  }
                } else {
                  if (v2.s != 63) {
                    v2.mhp *= 1.45;
                    v2.hp *= 1.45;
                    v2._yscale = 115;
                    v2._xscale = 115;
                  }
                }
                break;
              case 22:
                v2.mhp *= 2;
                v2.hp *= 2;
              case 20:
                v2._yscale = 75;
                v2._xscale = 75;
            }
          }
        }
        if (v2.champion) {
          specialColoring(v2);
          v2.hp *= 2;
          v2._xscale *= 1.15;
          v2._yscale *= 1.15;
        }
        if (f7 == 38) {
          flox = v2;
        }
        v2.invincible = v2.s == 42 or v2.s == 44;
        switch (f7) {
          case 102:
            v2.state = 0;
            v2.xpp = v2.xp;
            v2.ypp = v2.yp;
            break;
          case 19:
            if (altboss) {
              f1 = 1.3;
              v2.hp *= f1;
              v2.mhp *= f1;
            }
            break;
          case 67:
          case 65:
            if (altboss) {
              f1 = 1.3;
              v2.hp *= f1;
              v2.mhp *= f1;
            }
            break;
          case 101:
            v2.d._xscale *= 1.15;
            v2.d._yscale *= 1.15;
            v2.dfr = true;
            v2.xpp = v2.xp;
            v2.ypp = v2.yp;
            v2.d.gotoAndStop(1);
            v2.stomps = 0;
            break;
          case 100:
            boils = 0;
            if (altboss) {
              f1 = 0.85;
            } else {
              f1 = 0.52;
            }
            v2.hp *= f1;
            v2.mhp *= f1;
            break;
          case 91:
            v2.flyby = true;
            break;
          case 99:
            v2.fire = 0;
            break;
          case 69:
            if (altboss) {
              v2.hp *= 0.5;
              v2.mhp *= 0.5;
              if (!swag) {
                swag = true;
                spaw(v2.xp, v2.yp, 100, 69);
              }
            }
            break;
          case 71:
          case 72:
          case 73:
          case 67:
            v2.flyby = 2;
            if (altboss) {
              v2.hp *= 1.8;
              v2.mhp *= 1.8;
            }
            break;
          case 79:
            v2.fire = 0;
            break;
          case 97:
            altboss = false;
            trg2 = spaw(v2.xp, v2.yp, 40, 98);
            v2.trg2 = trg2;
            v2.invincible = true;
            v2.xbeww = v2.xbew;
            v2.ybeww = v2.ybew;
            break;
          case 92:
            hearts.push(v2);
            break;
          case 93:
            v2.trg2 = masks.length;
            masks.push(v2);
            v2.invincible = true;
            v2.xbeww = v2.xbew;
            v2.ybeww = v2.ybew;
            break;
          case 44:
            v2.xp = xenf;
            v2.xppp = v2.xp;
            v2.yp = yenf;
            v2.yppp = v2.yp;
          case 89:
            f1 = ingrid(v2.xp, v2.yp);
            outgrid(f1);
            break;
          case 85:
            if (fra > 20) {
              v2.hp *= 0.65;
              v2.mhp *= 0.65;
            }
          case 94:
            v2.outway = true;
            v2.wait = 0;
            break;
          case 46:
            v2.spl = 30;
            break;
          case 68:
            _root.slugeye = 1;
            break;
          case 51:
            v2.tier = 0;
            break;
          case 72:
            v2.d.gotoAndStop(7);
            break;
          case 73:
            v2.d.gotoAndStop(10);
            break;
          case 64:
            v2.spl = 30;
            v2.outway = true;
            break;
          case 62:
            if (altboss) {
              v2.hp *= 0.35;
              v2.mhp *= 0.35;
            } else {
              v2.hp *= 1.35;
              v2.mhp *= 1.35;
            }
            v2.dy = v2.d._y;
            v2.worm = 1;
            v2.outway = true;
            break;
          case 78:
            _root.soundy('Mom_Vox_Filtered_Isaac_' + random(3) + '.mp');
            player.xp = 320;
            player.yp = 370;
            v2.d.gotoAndStop(4);
            v2.downbro = 100;
            v2.wave = 0;
            v2.fire = 0;
          case 59:
          case 60:
          case 56:
            v2.xpp = v2.xp;
            v2.ypp = v2.yp;
            break;
          case 55:
          case 90:
            v2.flyby = true;
          case 31:
          case 23:
          case 21:
            v2.pbh = true;
            break;
          case 45:
            v2.alter = 1;
            if (_root.pillItem != 25) {
              player.xp = 320;
              player.yp = 370;
            }
            v2.spl = 0;
            v2.outway = true;
            v2.d.gotoAndStop(1);
            break;
          case 42:
            v2.xpp = v2.xp;
            v2.ypp = v2.yp;
            v2.til = ingrid(v2.xp, v2.yp);
            levz[v2.til] = 3;
            break;
          case 40:
            v2.outway = true;
            break;
          case 38:
            v2.telp = 0;
            v2.flyby = true;
            break;
          case 37:
            v2.bh = false;
            break;
          case 36:
            v2.yp += 25;
            v2.xpp = v2.xp;
            v2.ypp = v2.yp;
            player.xp = 320;
            player.yp = 400;
            break;
          case 32:
            v2.pbh = true;
            v2.rrr = random(4) * 0.06 + 0.9;
            break;
          case 33:
            v2.ggh = true;
            v2.nod = true;
            v2.bh = false;
            break;
          case 30:
            v2.hppp = 0;
            if (!v5) {
              v2.hp = 7;
            }
            v2.xpp = v2.xp;
            v2.ypp = v2.yp;
            break;
          case 25:
            v2.flyby = true;
            break;
          case 3:
            v2.lfra = 0;
            break;
          case 28:
            if (altboss == 2) {
              chubber = 0;
              v2.hp *= 0.5;
              v2.mhp *= 0.5;
            }
            v2.fail2 = 0;
            v2.beenx = [v2.xp];
            v2.beeny = [v2.yp];
            break;
          case 4:
            v2.lfra = fra;
            v2.spl = -10;
            break;
          case 16:
            v2.noco = 0;
            break;
          case 5:  //Pickups and junk
            v2.ph = true;
            v2.bh = false;
            v2.d.gotoAndStop(Math.max(1, Math.round(v5 * 100 - 0.499)));
            if (v2.d._currentframe == 11 or v2.d._currentframe == 16) {
              v2.d.prevFrame();
            }
            if (v2.d._currentframe != 7) {
              f1 = Math.round(v5 * 1000000000) - Math.round(v5 * 10000000) * 100;
            } else {
              f1 = Math.round(v5 * 1000000000) - Math.round(v2.d._currentframe * 100000) * 100;
            }
            if (fra > 10) {
              switch (v2.d._currentframe) {
                  if (v2.d._currentframe !== 6) {
                  } else {
                  case 5:
                    _root.soundy('Chest_Drop.mp', 100);
                  }
              }
            }
            if (v2.d._currentframe == 8 or v2.d._currentframe == 38) { //Slot Machine
              if (random(3) == 0 && !beenHere or v2.d._currentframe == 38 or _root.lev == _root.secretRoom2) {
                v2.col = 41;	//Fortune Teller Machine
              }
            }
            if (v2.d._currentframe == 31) { //Blood Donation Machines
              v2.d.gotoAndStop(8);
              v2.col = 1;
            }
            if (v2.d._currentframe == 32 or v2.d._currentframe == 37) { //Beggar
              v2.d.gotoAndStop(8);
              v2.col = 2;		//Regular Beggar
              if (random(3) == 0 && !beenHere or v2.d._currentframe == 37) {
                v2.col = 31;	//Demon Beggar
              }
            }
            if (v2.d._currentframe == 33) {
              v2.d.gotoAndStop(8);
              v2.col = 10;
            }
            if (f1 > 0) {	//For specific drops.
              v2.col = f1;
              if (f1 == 2 && v2.d._currentframe == 5) {
                v2.c2 = true;
              }
            } else {		//Modifiers, for random drops.
              if (v2.d._currentframe == 7) {	//Pill
                v2.col = random(6) + 1;
              }
              if (v2.d._currentframe == 3) {	//Golden Key
                v2.col = 1;
                if (random(50) == 1) {
                  v2.col = 2;
                }
              }
              if (v2.d._currentframe == 30) {	//Tarot Card
                v2.d.gotoAndStop(7);
                v5 = 0;
                v2.col = dropTarotCard();
              }
              if (v2.d._currentframe == 35) {	//Trinket
                v2.d.gotoAndStop(7);
                v5 = 0;
                v2.col = dropTrinket();
              }
              if (v2.d._currentframe == 36 or (v2.d._currentframe == 5 or haveTrinket(61) && v2.d._currentframe == 6) && ((haveTrinket(61) or random(20) == 0) && !beenHere or _root.lev == _root.curseRoom or _root.lev == _root.secretRoom2)) { //Red Chests
                v2.d.gotoAndStop(5);
                v5 = 0;
                v2.col = 2;
                v2.c2 = true;
              }
              if (v2.d._currentframe == 2 or v2.d._currentframe == 1 or v2.d._currentframe == 4) {
                f1 = [0, 2, 20, 0, 7];
                if (random(f1[v2.d._currentframe]) == 0) {
                  v2.col = 2;
                } else {
                  v2.col = 1;
                }
                if (v2.d._currentframe == 4 && random(50) == 0) { //Super Troll Bomb
                  v2.col = 5;
                }
                if (v2.d._currentframe == 2 && random(100) == 0) { //Dime
                  v2.col = 3;
                }
                if (v2.d._currentframe == 1 && random(50) == 0) { //Eternal Heart
                  v2.col = 4;
                }
                if (v2.d._currentframe == 4 && random(10) == 0) { //Troll Bomb
                  v2.col = 3;
                }
                if (v2.d._currentframe == 1 && (random(10) == 0 or random(16) == 0 && _root.characterID == 5 or haveTrinket(38) && random(10) == 0 or haveEffect[173] && random(2) == 0)) { //Soul Heart
                  v2.col = 3;
                }
                if (v2.d._currentframe == 1 && _root.lev == _root.secretRoom2) {
                  if (_root.secretRoom2Type == 0) { //Womb Secret Room
                    v2.col = 1;						//Half Heart
                  }
                  if (_root.secretRoom2Type == 1) {	//Cathedral Secret Room
                    v2.col = 4;						//Eternal Heart
                  }
                }
              }
            }
            if (v2.d._currentframe != 8) {
              if (v2.c2) {
                v2.d.d.gotoAndStop(7);
              } else {
                v2.d.d.gotoAndStop(3);
              }
            }
            if (v2.d._currentframe == 34) {	//Cathedral Portal, End Chest?
              if (_root.heaven && _root.floorNum != 11) {
                v2.d.d.gotoAndStop(5);
              } else {
                v2.d.d.gotoAndStop(3);
              }
            }
            it1[4] = false;
            if (Math.round(v5 * 100) >= 15 && Math.round(v5 * 100) < 20) {
              if (v5 > 0.1500000001) {
                v2.d.d.gotoAndStop(Math.round((v5 - 0.1500499) * 1000));
              } else {
                if (satan) {
                  if (random(5) == 0) {
                    v2.d.d.gotoAndStop(11);				//3 Soul Hearts
                  } else {
                    v2.d.d.gotoAndStop(9 + random(2));	//1/2 Heart Containers
                  }
                } else {
                  f1 = -1;
                  while (!it1[f1]) {
                    f1 = random(7);
                  }
                  if (f1 == 4 or f1 == 3) {
                    watz = -100;
                  } else {
                    ++watz;
                  }
                  if (watz > 1 or watz == 1 && random(3) == 0) {
                    f1 = 3;
                    watz = -100;
                  }
                  it1[f1] = false;
                  if (f1 == 4) {
                    f1 = 3;
                  } else {
                    if (f1 > 4) {
                      f1 += 6;
                    }
                  }
                  v2.d.d.gotoAndStop(f1 + 1);
                  v2.shopProduct = true;
                  if (v2.d.d._currentframe == 3) {	//Pill
                    v2.col = random(15) + 1;
                  }
                  if (v2.d.d._currentframe == 13) {	//Soul Heart
                    v2.col = 3;
                  }
                }
              }
              if (v2.shopProduct && random(5) == 0 && !salefail && (v2.d.d._currentframe < 5 or v2.d.d._currentframe == 12 or v2.d.d._currentframe == 13)) {
                salefail = true;
                v2.d.d.gotoAndStop(v2.d.d._currentframe + 4);
              }
              if (v2.d.d._currentframe == 3 or v2.d.d._currentframe == 7) {	//Pill
                v2.d.d.d.gotoAndStop(v2.col);
              }
              if (v2.d.d._currentframe == 13 or v2.d.d._currentframe == 17) {	//Soul Heart
                v2.d.d.d.d.d.gotoAndStop(3);
              }
              if (v2.d.d._currentframe == 4 or v2.d.d._currentframe >= 8 && v2.d.d._currentframe < 12) {	//Shop Treasure
                _root.trg = v2;
                if (v5 >= 0.1504 && v5 < 0.4) {
                  v2.it = Math.round((v5 - 0.15 - v2.d.d._currentframe * 0.001) * 1000000);
                } else {
                  v2.it = GenerateItem();
                }
                v2.d.d.d.gotoAndStop(v2.it);
              }
            } else {
              if (v5 > 0.09 && v5 < 0.2) {
                if (v5 > 0.1 && v5 < 0.4) {
                  v2.it = Math.round((v5 - 0.1) * 10000);
                } else {
                  v2.it = GenerateItem();
                }
                v2.d.d.d.d.gotoAndStop(v2.it);
              }
            }
            v2.xpp = v2.xp;
            v2.ypp = v2.yp;
            if (v2.d._currentframe == 8 && v2.col != 41) {
              if (v2.col == 10) {
                v2.d.d.gotoAndStop(41);
              } else {
                if (v2.col == 1) {
                  v2.d.d.gotoAndStop(32);
                } else {
                  if (v2.col > 1) {
                    v2.d.d.gotoAndStop(36);
                  }
                }
              }
            }
            break;
          case 61:
          case 13:
          case 14:
          case 18:
          case 80:
            v2.flyai = true;
            v2.d.d.d.gotoAndPlay(random(2) + 1);
            v2.ybb = 0;
            v2.xbb = 0;
            break;
          case 12:
            break;
          case 7:
          case 8:
            if (f7 == 8) {
              var v12 = new flash.geom.Transform(v2);
              v12.colorTransform = bloc;
            }
            v2.ypp = v2.ybew;
            v2.bh = false;
            v2.d._rotation = random(360);
            v2.fd = 1.3;
            if (f7 == 7) {
              v2.spl = 10;
            } else {
              v2.spl = 0;
            }
            v2.dm = -random(30) + 5;
            v2.dy = -23;
            75;
            break;
          case 9:
            v2.dy = -23;
            75;
            v2.shot = true;
            v2.ph = true;
            v2.spl = 0;
            v2.dm = rand() * 0.2;
            break;
          case 2: //Tears
            if (haveEffect[143] or haveEffect[165] or haveEffect[183] or haveEffect[176] or haveEffect[182] or haveEffect[194] or _root.characterID == 6) {
              var tearSpeed = 1 + haveEffect[143] * 0.2 + haveEffect[165] * 0.23 + haveEffect[176] * 0.16 + (haveEffect[183] + haveEffect[194]) * 0.16 - haveEffect[182] * 0.25;
              if (_root.characterID == 6) {
                tearSpeed += 0.31;
              }
              tearSpeed = Math.min(tearSpeed, 1.4);
              v2.xbew *= tearSpeed;
              v2.ybew *= tearSpeed;
            }
            v2.dy = -23;
            75;
            v2.spl = 10;
            v2.dm = rand() * 0.2;
            if (babymode) {
              v2.ba = babymode;
              v2.dmg = 3.5;
              if (babymode == 10) {
                v2.ics = true;
              } else {
                if (babymode == 6) {
                  v2._alpha = 50;
                } else {
                  if (babymode == 7) {
                    v2.dmg = 4;
                    attach(v2, 500);
                    v2.d._xscale = 90;
                    v2.d._yscale = v2.d._xscale;
                    v2.spl = 0;
                  } else {
                    if (babymode == 5) {
                      v2.dmg = 3;
                      attach(v2, 500);
                      v2.d._xscale = 80;
                      v2.d._yscale = v2.d._xscale;
                      v2.spl = 0;
                      v2.dm = 1.2;
                    } else {
                      if (babymode == 2) {
                        v2.dmg = 5;
                        attach(v2, 500);
                        v2.d._xscale = 106;
                        v2.d._yscale = v2.d._xscale;
                        v2.spl = 0;
                      } else {
                        if (babymode == 3) {
                          colorit(v2, 0.95, 0.8, 0.6, -150, -150, -150);
                        } else {
                          if (babymode == 4 or babymode == 11) {
                            colorit(v2, 0.4, 0.15, 0.38, 71, 0, 116);
                            if (babymode == 11) {
                              v2._alpha = 50;
                            }
                            v2.dm -= 3;
                          }
                        }
                      }
                    }
                  }
                }
              }
              babymode = undefined;
            } else {
              v2.dmg = baseDamage();
              if (haveTrinket(30)) {
                if (random(10) == 0) {
                  v2.trinketTears = 1;
                }
              }
              if (haveTrinket(31)) {
                if (random(10) == 0) {
                  v2.trinketTears = 2;
                }
              }
              if (haveEffect[150] && random(10 - _root.luck) == 0) {
                v2.dmg *= 3.2;
                attach(v2, 499);
                if (v2.xbew < 0) {
                  v2.d.d._xscale *= -1;
                }
                if (v2.trinketTears == 2) {
                  colorit(v2, 1.5, 2, 2, 0, 0, 0);
                }
                v2.spl = 0;
                v2.spll = true;
                v2.tooth = true;
                v2.d._xscale = 70;
                v2.d._yscale = v2.d._xscale;
              } else {
                if (v2.trinketTears == 2) {
                  colorit(v2, 1.5, 2, 2, 0, 0, 0);
                } else {
                  if (v2.trinketTears == 1) {
                    v2.spl = 30;
                    colorit(v2, 0.5, 0.97, 0.5, 0, 0, 0);
                  } else {
                    if (haveEffect[182]) {
                      colorit(v2, 1.5, 2, 2, 0, 0, 0);
                    } else {
                      if (!haveEffect[149] && (haveEffect[189] or haveEffect[7] or haveEffect[183] or belial or demon > 0 or v2.dmg > 5.5 && (!haveEffect[169] or v2.dmg > 15) && !haveEffect[69] or haveEffect[122] or sob == -1 && haveEffect[155])) {
                        attach(v2, 500);
                        v2.d._xscale = 90;
                        v2.d._yscale = v2.d._xscale;
                        v2.spl = 0;
                      } else {
                        if (haveEffect[115]) {
                          colorit(v2, 1.5, 2, 2, 0, 0, 0);
                        } else {
                          if (haveEffect[132]) {
                            colorit(v2, 0.2, 0.09, 0.065, 0, 0, 0);
                          } else {
                            if (haveEffect[103]) {
                              v2.spl = 30;
                              colorit(v2, 0.5, 0.97, 0.5, 0, 0, 0);
                            } else {
                              if (haveEffect[104]) {
                                colorit(v2, 0.9, 0.3, 0.08, 0, 0, 0);
                              } else {
                                if (haveEffect[90]) {
                                  colorit(v2, 0.4, 0.4, 0.4, 50, 50, 50);
                                } else {
                                  if (haveEffect[110]) {
                                    v2.spl = 0;
                                    colorit(v2, 1.25, 0.05, 0.15, 0, 0, 0);
                                  } else {
                                    if (haveEffect[89]) {
                                      colorit(v2, 2, 2, 2, 50, 50, 50);
                                    } else {
                                      if (haveEffect[69]) {
                                        colorit(v2, 0.33, 0.18, 0.18, 66, 40, 40);
                                        v2.d._xscale *= 1 + (chal - 1) * 0.05;
                                      } else {
                                        if (haveEffect[6]) {
                                          colorit(v2, 1, 1, 0, 45, 15, 0);
                                          v2.spl = 20;
                                          v2.piss = true;
                                        } else {
                                          if (haveEffect[3]) {
                                            colorit(v2, 0.4, 0.15, 0.38, 71, 0, 116);
                                          }
                                        }
                                      }
                                    }
                                  }
                                }
                              }
                            }
                          }
                        }
                      }
                    }
                  }
                }
              }
              if (haveEffect[132]) {
                v2.coalSize = 0;
                v2.d._xscale -= 15;
                v2.d._yscale -= 15;
              }
              if (haveEffect[115] or v2.trinketTears == 2) {
                v2._alpha = 50;
              }
              if (haveEffect[6]) {
                v2.dy += 13;
              } else {
                if (_root.characterID == 2) {
                  v2.dy += 6;
                } else {
                  if (_root.characterID == 6) {
                    v2.dy += 5;
                  }
                }
              }
            }
            v2.nuts = 0.2;
            v2.dir = Math.abs(v2.xbew) < Math.abs(v2.ybew);
            v2.hh = [];
            v2.shot = true;
            if (!v2.ba) {
              if (haveEffect[5]) {
                v2.xbew *= 1.6;
                v2.ybew *= 1.6;
              }
              v2.dy -= (haveEffect[12] - haveEffect[71] + haveEffect[30] + haveEffect[31] + haveEffect[29]) * 5;
              if (haveEffect[4] or belial && haveEffect[7] or haveEffect[12]) {
                v2.dmg *= 1.5;
              }
              f1 = haveEffect[12] + haveEffect[30] + haveEffect[31] + haveEffect[29] + haveEffect[71] * 3 + haveEffect[101] + haveEffect[110] + haveEffect[121] + haveEffect[182] * 1.5 + haveEffect[197];
              f1 *= 0.5;
              v2.dm -= f1;
              v2.dy -= f1 * 0.5;
              _root.tearRange = -v2.dm * 5 - v2.dy;
            }
            f1 = 0.7 + v2.dmg * 0.04 + Math.sqrt(v2.dmg) * 0.15;
            v2.d._xscale *= f1;
            v2.d._yscale = v2.d._xscale;
            break;
          case 11:
            v2.bnuts = !v5;
            break;
          case 10:
            v2.gonuts = !v5;
            v2.bnuts = random(3) == 0;
        }
        if (haveTrinket(53) && v2.hp > 60) {
          v2.hp *= 0.85;
        }
        if (f7 == 45) {
          v2.d.gotoAndStop(1);
        }
        return v2;
      }

      function parc(f1, f2, f3, f4, f5, f6) {
        dang = true;
        ++parz;
        namer = 'p' + parz;
        f0 = par.length;
        if (f6 == undefined) {
          f6 = parz + 100000;
        }
        if (f1 == 'bloo') {
          par[f0] = blorz.attachMovie(f1, namer, f6);
        } else {
          par[f0] = attachMovie(f1, namer, f6);
        }
        par[f0]._x = f2;
        par[f0]._y = f3;
        if (f4) {
          par[f0]._rotation = f4;
        }
        if (f5) {
          par[f0]._yscale = f5;
          par[f0]._xscale = par[f0]._yscale;
        }
        par[f0].stop();
        return par[f0];
      }

      function rotc(f0) {
        return f0;
      }

      function rand() {
        return Math.random() - 0.5;
      }

      function rotrund(f1) {
        while (f1 > 180) {
          f1 -= 360;
        }
        while (f1 < -180) {
          f1 += 360;
        }
        return f1;
      }

      function rotget(f1, f2) {
        f0 = (Math.atan(-f1 / f2) / Math.PI) * 180 + 90;
        if (f2 >= 0) {
          f0 += 180;
        }
        return f0;
      }

      function linearcut(f1, f2, f3, f4, f5, f6) {
        return (f1 * f6 - f2 * f5) / (f3 * f6 - f5 * f4);
      }

      function absmax(f1, f2) {
        if (f1 > f2) {
          f1 = f2;
          return f1;
        }
        if (f1 < -f2) {
          f1 = -f2;
        }
        return f1;
      }

      function enfget(f1, f2) {
        f1 = f1 * f1 + f2 * f2;
        if (f1 > 0) {
          f1 = Math.sqrt(f1);
          return f1;
        }
        f1 = 0.001;
        return f1;
      }

      function enfcheckx(f1, f2, f3, f4, siz) {
        xenf = f1 - f3;
        yenf = f2 - f4;
        if (Math.abs(xenf) < roxx2 or Math.abs(yenf) < roxx2) {
          enf = enfget(xenf, yenf);
          if (enf < siz) {
            return enf;
          }
        }
      }

      function enfcheck(f1, f2, f3, f4, siz) {
        xenf = f1 - f3;
        if (Math.abs(xenf) < siz) {
          yenf = f2 - f4;
          if (Math.abs(yenf) < siz) {
            enf = enfget(xenf, yenf);
            if (enf < siz) {
              return enf;
            }
          }
        }
      }

      function t3d(f1, f2) {
        f2 += f1._rotation;
        f2 += 45;
        while (f2 > 360) {
          f2 -= 360;
        }
        while (f2 < 0) {
          f2 += 360;
        }
        f1.gotoAndStop(Math.round((f2 / 360) * 72) + 1);
      }

      function pff(f1, f2) {
        if (trg.gridder[f1] >= 0 && trg.gridder[f1] < 1) {
          if (trg.gridder[f1] == 0) {
            --f2;
          } else {
            f2 -= 7;
          }
          trg.gridder[f1] = f2;
          acts2.push(f1);
        }
      }

      function pff1(f1, f2) {
        if (trg.gridder[f1] + f2 * 3 > v3 && trg.gridder[f1] < 0) {
          v3 = trg.gridder[f1];
          v4 = f1;
        }
      }

      function pff2(f1) {
        if (levz[f1] != 0) {
          outgrid(f1);
          if (Math.abs(xenf) > 0 && Math.abs(yenf) > 0) {
            if (Math.abs(xenf - trg.xp) < roxx * 0.8 && Math.abs(yenf - trg.yp) < roxx * 0.8) {
              if (xenf < trg.xp) {
                minx = xenf + roxx * 0.8;
              } else {
                maxx = xenf - roxx * 0.8;
              }
              if (yenf < trg.xp) {
                miny = yenf + roxx * 0.8;
              } else {
                maxy = yenf - roxx * 0.8;
              }
            }
          }
        }
      }

      function momkill() {
        if (momdown != 100) {
          for (z in ball) {
            momdown = 100;
            if (_root.floorNum == 6) {		//Mom Death
              _root.soundy('Mom_Vox_Death_' + random(2) + '.mp');
            } else {
              if (_root.floorNum == 9) {
              } else {						//Mom Heart Death
                _root.soundy('Mom_Vox_Filtered_Death_1.mp');
              }
            }
            if (trg.s != 78) {
              hurt(ball[z], 100);
            }
          }
        }
        momHeart._visible = false;
      }

      function hurt(trg, f1) {
        if (trg == momHeart) {
          momHeart.downbro -= 3;
        }
        if (trg.s == 45) {	//Mom's cries of pain
          if (f1 > 10 + random(20)) {
            if (trriss + 25 + random(30) <= fra) {
              trriss = fra;
              _root.soundy('Mom_Vox_Hurt_' + random(4) + '.mp');
            }
          }
        }
        if (trg.s == 102) {	//Isaac/???'s Retaliation
          trg.isaacRetaliation = true;
        }
        if (trg == momHeart) {	//Mom's Heart's cries of pain
          if (f1 > 10 + random(20)) {
            if (trriss + 25 + random(30) <= fra) {
              trriss = fra;
              _root.soundy('Mom_Vox_Filtered_Hurt_' + random(4) + '.mp');
            }
          }
        }
        if (trg.randd + 2 > fra && random(5) == 0) {
          trg.xpp = trg.xp;
          trg.ypp = trg.yp;
        }
        if (!trg.dones) {
          if (trg.s == 30) {
            trg.hppp = 0;
          }
          if (trg.s == 38) {
            trg.telp = 20;
          }
          if (trg.invincible) {
            f1 = 0;
          }
          if (trg.s == 62) {
            if (trg.worm == 1 && trg.d._currentframe == 8 or altboss) {
              trg = worm[6];
            } else {
              if (trg.worm != 6) {
                f1 = 0;
                lows.dones = false;
              } else {
                f1 *= 5;
              }
            }
          }
          if (trg.s == 27 && trg.alter != 2) {
            trg.fire = Math.min(10, trg.fire + f1);
            if (f1 > 10) {
              trg.d.t._visible = true;
              trg.d.t.t.gotoAndPlay(1);
            }
          }
          if (f1 > 0 && trg.mhp > 0 && trg != player && (trg.d.d.open or trg.s != 27 or trg.alter == 2 or lows.meat > 2 or lows.bird)) {
            if (trg.s == 19) {
              if (!trg.whop) {
                trg.whop = -1;
              }
            } else {
              if (trg.s == 21) {
                trg.xpp = undefined;
              }
            }
            if (trg.s == 45) {
              for (z in mom) {
                mom[z].hp -= f1;
              }
            } else {
              if (trg.s == 28) {
                trg.mags[1].hp -= f1;
                trg.mags[2].hp -= f1;
                trg.mags[3].hp -= f1;
              } else {
                trg.hp -= f1;
              }
            }
            if (trg.hp < 0) { //Monster Destroyed
              if (trg.s == 99 && trg.hp < 0) {
                _root.soundy('Monster_Roar_2.mp', 120);
              }
              if (pacman) {
                if (!paccer) {
                  player.hp += 0.5;
                }
                paccer = !paccer;
              }
              if (trg.poisonDuration > 0) {
                trg.spl = 30;
              }
              if (trg == momHeart) {	//Mom's Heart Kill
                momkill();
              }
              if (trg.s == 84 && trg.satanPhase > 3) { //Satan Kill
                momkill();
              }
              if (haveEffect[157]) {	//Bloody Lust
                rage = Math.min(3.3, rage + 0.28);
                rag = rage * 0.32 + 0.6800000000000001;
              }
              if (haveTrinket(58) && random(15) == 0) {	//Samson's Lock
                rage = Math.min(3.3, rage + 0.5);
                rag = rage * 0.32 + 0.6800000000000001;
              }
              if (haveTrinket(60) && random(20) == 0) {	//Eve's Bird Foot
                if (!dbird && ashut > 1) {
                  dbird = 2;
                }
              }
              if (!trg.flyai && haveEffect[62] && trg.s >= 10) {	//Charm of the Vampire
                if (_root.charmOfTheVampire++ >= 12 && player.mhp > 0) {
                  _root.charmOfTheVampire = 0;
                  player.hp += 0.5;
                  parc('hearter', player.xp, player.yp - 20, 0, 100, player.dpppp + 5000);
                  _root.soundy('Vamp_Gulp.mp');
                }
              }
              if (trg.s == 62) {
                for (z in worm) {
                  worm[z].dones = true;
                }
              } else {
                if (trg.s == 45) {
                  for (z in mom) {
                    mom[z].dones = true;
                    mom[z]._visible = false;
                  }
                  momkill();
                } else {
                  if (trg.s == 28) {
                    _root.soundy('Monster_Roar_2.mp', 50);
                    trg.mags[1].dones = true;
                    trg.mags[2].dones = true;
                    trg.mags[3].dones = true;
                  }
                }
              }
              if (trg.s == 89) {
                trg.trg3.frei = true;
                trg.trg2.frei = true;
                trg.frei = true;
              }
              if (trg.s == 74) {
                trg.d.gotoAndStop(6);
              } else {
                if (trg.s == 75) {
                  trg.d.gotoAndStop(9);
                } else {
                  if (trg.s == 15 && random(2) == 0 && !blackout == 2) {
                    trg.gosplash = true;
                    trg.s = 17;
                    attach(trg, 17);
                    trg.hp = hps[trg.s];
                    trg.ypp = 0;
                    trg.xpp = 0;
                  } else {
                    if (trg.s == 10 && random(2) == 0 && trg.hp > -25) {
                      trg.gosplash = true;
                      attach(trg, 11);
                      trg.s = 11;
                      trg.outway = true;
                      trg.hp = hps[trg.s];
                      splater(trg.xp, trg.yp, random(10) + 1, Math.random() + 0.6);
                    } else {
                      if (trg.s == 24 && trg.d._currentframe < 3) {
                        trg.gosplash = true;
                        trg.d.gotoAndStop(5);
                        trg.outway = true;
                        trg.hp = 10;
                        splater(trg.xp, trg.yp, random(10) + 1, Math.random() + 0.6);
                      } else {
                        if (trg.s == 84) {
                          ++trg.satanPhase;
                          if (trg.satanPhase == 4) {
                            trg.hp = trg.mhp;
                            trg.d.gotoAndStop(8);
                            trg.bh = false;
                          }
                        } else {
                          trg.dones = true;
                        }
                      }
                    }
                  }
                }
              }
            } else {
              colorit(trg, 0.5, 0.5, 0.5, 200, 0, 0);
              trg.uncol = Math.round(fra + Math.min(6, f1 / 1.5));
              if (trg.hbar) {
                _root.hud.bar.bar.gotoAndPlay(1);
              }
              if (trg.s == 62) {
                trg.uncol = Math.round(fra + Math.min(6, f1 / 1.5));
                for (z in worm) {
                  if (worm[z].bh) {
                    colorit(worm[z], 0.5, 0.5, 0.5, 200, 0, 0);
                    worm[z].uncol = trg.uncol;
                  }
                }
              } else {
                if (trg.s == 45) {
                  trg.uncol = Math.round(fra + 1);
                  for (z in mom) {
                    if (mom[z].bh or mom[z].mom == 3) {
                      colorit(mom[z], 0.5, 0.5, 0.5, 200, 0, 0);
                      mom[z].uncol = trg.uncol;
                    }
                  }
                  trg.uncol = Math.round(fra + Math.min(6, f1 / 1.5));
                } else {
                  if (trg.s == 28) {
                    colorit(trg.mags[1], 0.5, 0.5, 0.5, 200, 0, 0);
                    trg.mags[1].uncol = trg.uncol;
                    colorit(trg.mags[2], 0.5, 0.5, 0.5, 200, 0, 0);
                    trg.mags[2].uncol = trg.uncol;
                    colorit(trg.mags[3], 0.5, 0.5, 0.5, 200, 0, 0);
                    trg.mags[3].uncol = trg.uncol;
                  }
                }
              }
            }
          }
        }
      }

      function colorit(trg, f1, f2, f3, f4, f5, f6) {
        var v1 = new flash.geom.ColorTransform();
        v1.redMultiplier = f1;
        v1.greenMultiplier = f2;
        v1.blueMultiplier = f3;
        v1.redOffset = f4;
        v1.greenOffset = f5;
        v1.blueOffset = f6;
        var v3 = new flash.geom.Transform(trg);
        if (trg.s == 9 or trg.s == 8) {
          trg.colo = v1;
        }
        v3.colorTransform = v1;
      }

      function pillTintPlayer(f1, f2, f3) {
        colorit(player, 0.3, 0.3, 0.3, f1 * 1.3, f2 * 1.3, f3 * 1.3);
        pillef = fra + 30;
        _root.playerTint[0] *= 0.4;
        _root.playerTint[1] *= 0.4;
        _root.playerTint[2] *= 0.4;
        _root.playerTint[0] += f1 / 160;
        _root.playerTint[1] += f2 / 160;
        _root.playerTint[2] += f3 / 160;
      }

      function colorPlayer(f1) {
        if (pillef > fra) {
          player._alpha = 100;
        } else {
          if (unic > 30 && !pacman) {
            if (unic % 4 == 0 && player.d._currentframe < 4) {
              v1 = 50;
              v2 = 70;
              if (roll(6)) {
                colorit(player, 1, 0, 0, v1, v1, v1);
              } else {
                if (roll()) {
                  colorit(player, 0, 1, 0, v1, v1, v1);
                } else {
                  if (roll()) {
                    colorit(player, 0, 0, 1, v1, v1, v1);
                  } else {
                    if (roll()) {
                      colorit(player, 1, 1, 0, v2, v2, v2);
                    } else {
                      if (roll()) {
                        colorit(player, 0, 1, 1, v2, v2, v2);
                      } else {
                        if (roll()) {
                          colorit(player, 1, 0, 1, v2, v2, v2);
                        }
                      }
                    }
                  }
                }
              }
            }
          } else {
            if (f1) {
              player._alpha = 0;
            } else {
              if (!trg.free) {
                player._alpha = 100;
                if (rage != 1) {
                  colorit(player, _root.playerTint[0] * rag, _root.playerTint[1] / rag, _root.playerTint[2] / rag, 0, 0, 0);
                } else {
                  colorit(player, _root.playerTint[0], _root.playerTint[1], _root.playerTint[2], 0, 0, 0);
                }
              }
            }
          }
        }
      }

      function teleport() {
        player.d.gotoAndStop(7);
        telf = fra + player.d.d._totalframes - 3;
        _root.soundy('hell_portal2.wav');
      }

      function haveTrinket(f111) {
        return _root.trinketSlot1 == f111 or _root.trinketslot2 == f111;
      }

      function playerhurt(f1, f2, f3) {
        if (_root.floorNum > 6) {	//All damage is at least 1 heart after Depths/Necropolis 2
          f1 = Math.max(f1, 1);
        }
        if (haveEffect[108]) {
          f1 = 0.5;
        }
        if (f2 == 45) {
          if (trrisx + 50 + random(130) <= fra) {
            trrisx = fra;
            _root.soundy('Mom_Vox_EvilLaugh.mp');
          }
        }
        if (_root.floorNum == 9 && _root.lev == _root.bossRoom) {
          plh = true;
        }
        if (mhheart) {
          if (trrisx + 50 + random(130) <= fra) {
            trrisx = fra;
            _root.soundy('Mom_Vox_Filtered_EvilLaugh.mp');
          }
        }
        if (lasth - fra < 0 && player._visible && telf == undefined && playsave < 0 && unic < 0 && player._currentframe != 6 && horse <= 0 && decoy <= 0) {
          if (f1 > 0) {
            lastk = f2;
            plah = true;
            if (f2 <= 200) {
              _root.nodmg = false;
            }
            if (_root.armor > 0) {
              _root.armor -= f1;
              if (_root.armor <= 0) {
                _root.armor = 0;
              }
            } else {
              if (_root.eternalHeart) {
                _root.eternalHeart = false;
                player.hp += 0.5;
              }
              _root.armor = 0;
              player.hp -= f1;
              if (_root.devil != 2 && _root.devil != 3 && f2 <= 200) {
                _root.devil = false;
              }
              if (f2 <= 200) {
                noBossDamage = false;
              }
            }
            if (haveEffect[148]) {
              blueFlies += 1 + random(3);
            }
            if (haveTrinket(29)) {
              ++blueFlies;
            }
            if (player.hp == 0 && _root.armor == 0.5 or player.hp == 0.5 && _root.armor <= 0) {
              if (haveTrinket(33)) {
                ++haveEffect[100];
              }
              if (haveEffect[142]) {
                ++_root.armor;
                haveEffect[142] = 0;
              }
            }
            if (holyWater != undefined) {
              trg3 = create(player.xp * 0.6 + holyWater.xp * 0.4, player.yp * 0.6 + holyWater.yp * 0.4, 0, 0, 0, 0, 33.1);
              colorit(trg3.d.d, 0.45, 0.7, 1, 0, 0, 70);
              _root.soundy('BGascan_pour.wav', 100);
              holyWater.stopi = true;
              holyWater.d.gotoAndStop(127);
              holyWater = undefined;
            }
            if (blueFlies > 1) {
              blueFlyTarget = highs;
            }
            if (haveTrinket(40) && random(5) == 0) {	//Red Patch
              razor += 3;
            }
            if (haveTrinket(48) && random(20) == 1) {	//Missing Page
              _root.over.gotoAndStop(3);
              _root.soundy('Death_Card.mp', 100);
              for (e in ball) {
                trg2 = ball[e];
                hurt(trg2, 40);
              }
            }
            if (haveEffect[156] && _root.itemCharges != 1) {	//Habit
              _root.itemCharges += 0.5;
              _root.soundy('batterycharge.mp');
              parc('batter', player.xp, player.yp - 20, 0, 100, player.dpppp + 5000);
            }
            lasth = fra + f1 * 60;
            if (_root.pickedUp[122] && !haveEffect[122] && player.hp > 0 && player.hp < 1) {
              haveEffect[122] = 1.2;
              curs();
              lasth = fra + 90;
            } else {
              if (haveEffect[117]) {
                haveEffect[117] = 0.55;
              }
            }
            if (haveEffect[162] && random(5) == 0) {
              playsave = 200;
            }
            if (demon > 0) {
              _root.soundy('Monster_Grunt_' + random(2) + '_B.mp');
            } else {
              _root.soundy('Isaac_Hurt_Grunt' + random(3) + '.mp');
            }
            if (haveEffect[180]) {
              farter = true;
            }
            if ((player.hp <= 0 && _root.armor <= 0 or !(player.mhp > 0 or _root.armor > 0)) && !f3) {
              player.d.gotoAndStop(6);
              player.d.d.gotoAndStop(sk);
              player.dones = true;
              return true;
            }
            if (f3 && player.hp <= 0) {
              player.hp = 0.5;
            }
            player.d.gotoAndStop(2);
            if (player.hp <= 0.5 or !(player.mhp > 0 or _root.armor > 0)) {
              if (haveTrinket(47)) {
                playsave = 150;
              }
              if (haveTrinket(43)) {
                teleport();
                teleportTarget = _root.lastl;
                if (_root.lev <= 0) {
                  teleportTarget = 35;
                  _root.lastl = 35;
                }
              }
            }
            return true;
          }
        }
      }

      function splater(f1, f2, f3, f4) {
        if (f3 >= 1) {
          blood.gotoAndStop(f3);
          v1 = f4;
          if (random(2) == 0) {
            v2 = -v1;
          } else {
            v2 = v1;
          }
          maxx = new flash.geom.Matrix();
          maxx.scale(v1, v2);
          maxx.translate(f1 + crand(5), f2 + crand(5) - 5);
          maxx.scale(hdx, hdx);
          splat.draw(blood, maxx, bloc);
        }
      }

      function shadow(f1, f2) {
        poi.x = f1;
        poi.y = f2;
        shad.copyPixels(org, org.rectangle, poi, undefined, undefined, true);
        maxx = new flash.geom.Matrix();
        maxx.translate(f1, f2);
        shad.draw(shaz, maxx);
      }

      function turd(f1, e, cent) {
        if (fra > 10 && levz[e] < 0.9300000000000001) {
          levz[e] = 1.5;
          clevzc[e] = 1.5;
        }
        if (levz[e] > 1.1) {
          var v6 = _root.levsav[_root.lev][savv];
          outgrid(e);
          f2 = 'de' + e * 1;
          if (f1 == 'fireblock2') {
            var v3 = attachMovie(f1, 'de' + f2, Math.round(e + 501), {'_x': xenf, '_y': yenf});
            v3.gotoAndStop(1);
            this[f2] = v3.d;
            v3 = v3.d;
            ref.push(v3);
            v3.fra = 0;
          } else {
            var v3 = attachMovie(f1, f2, Math.round(e + 501), {'_x': xenf, '_y': yenf});
          }
          if (f1 == 'breakblock2' or f1 == 'fireblock' or f1 == 'fireblock2') {
            v3.fire = true;
          }
          v3.xp = xenf;
          v3.yp = yenf;
          v3.cent = cent;
          v3.savv = savv;
          v3.nam = f1;
          v3.til = e;
          if (v6 > 0 && v3.nam != 'breakblock2') {
            v3.gotoAndStop(v6);
            if (levz[e] == 4) {
              levz[e] = 0;
            } else {
              levz[e] -= 0.13 * (v6 - 1);
            }
          }
          if (fra < 10) {
            v3.p.gotoAndStop(v3.p._totalframes);
          }
          if (fra > 10) {
            v3.gotoAndStop(6);
          }
          if (f1 == 'locktile' && v6 > 1) {
            v3.gotoAndStop(3);
          }
          ++savv;
          return v3;
        }
      }

      function upa() {
        haveEffect = _root.pickedUp.slice(0, -1);
        if (_root.cainsEye) { //Cain's Eye effect activates the compass.
          haveEffect[21] = true;
        }
        if (_root.world) { //World Card activates both map and compass.
          haveEffect[54] = true;
          haveEffect[21] = haveEffect[54]; //why not just set it to true wtf
        }
        if (haveEffect[69] && haveEffect[52]) { //Dr. Fetus gets rid of Chocolate Milk.
          haveEffect[69] = 0;
        }
        if (haveEffect[168]) { //Epic Fetus gets rid of...
          haveEffect[69] = 0;  //Chocolate Milk
          haveEffect[118] = 0; //Brimstone
          haveEffect[114] = 0; //Mom's Knife
        }
        if (haveEffect[114]) { //Mom's Knife gets rid of...
          haveEffect[118] = 0; //Brimstone
        }
        if (haveEffect[191]) { //3 Dollar Bill Effects
          f1 = [1, 2, 3, 5, 6, 46, 53, 110, 115, 143, 150];
          haveEffect[f1[random(f1.length)]] = 1;
        }
        if (_root.pickedUp[122]) { //Whore of Babylon check
          if (player.hp < 1) {
            haveEffect[122] = 1;
            sk = 7;
            cursed = true;
          } else {
            haveEffect[122] = 0;
          }
        }
        if (haveTrinket(32) && random(4) == 0) { //Liberty Cap Effects
          f1 = [21, 71, 120, 121]; //The Compass, Mini Mush, Odd Mushroom, Odd Mushroom
          haveEffect[f1[random(f1.length)]] = 1;
        }
      }

      function curs() {
        sk = 7;
        _root.mmus = _root.soundy('isaacsatanitemget.mp', 100);
        _root.over.gotoAndStop(13);
        player.d.gotoAndStop(11);
        player.it = 122;
      }

      function golev() {
        upa();
        if (_root.pickedUp[122]) { //Whore of Babylon check
          if (player.hp < 1) {
            haveEffect[122] = 1;
            cursed = true;
          } else {
            haveEffect[122] = 0;
          }
        }
        if (_root.characterID > 0 && _root.classit) {
          _root.classit = false;
          f10 = [0, 45, 46, 34, 36, 117, 157]; //Character's starting items.
          highs = player;                     //Get ready to load up the item...
          player.it = f10[_root.characterID]; //Load it up, hold it over their head...
          powerlevel();						  //And give it to them.
          if (_root.characterID == 5) {       //Eve has two starting items...
            _root.pickedUp[122] = 1;		  //So Let's give her The Dead Bird silently.
            _root.collectionScreen.push(122); //And add The Dead Bird to the Collection Screen...
          }									  //...since you didn't actually pick it up.
        }
        if (_root.challenge != 0) {				  //Are you playing a challenge?
          if (!_root.noDice) {
            _root.noDice = true;
            challengeStartingItems = [0, 0, 0, 0, [81], [151, 148], [52, 47], [73, 73, 73, 73], [153, 89], [101, 184]];
            startItems = challengeStartingItems[_root.challenge];
            challengeItem = true;
            for (e in startItems) {
              lastcra = -100;
              player.empty = false;
              highs = player;
              player.it = startItems[e];
              powerlevel();
            }
            challengeItem = undefined;
          }
        }
        if (!_root.noDice && _root.SecretUnlocked[38] && _root.characterID == 0 && _root.challenge == 0) {
          player.empty = false;
          lastcra = -100;
          _root.noDice = true;
          highs = player;
          player.it = 105;
          powerlevel();
        }
        if (_root.shroom) { //When you respawn on a floor, hold it over your head.
          player.d.gotoAndStop(4);
          if (_root.shroom == 4) {
            player.it = 161;	//Ankh
          } else {
            if (_root.shroom == 3) {
              player.it = 127;	//Forget Me Now
            } else {
              if (_root.shroom == 2) {
                player.it = 81; //Dead Cat
              } else {
                player.it = 11;	//1-up Mushroom
                _root.soundy('1up.wav');
              }
            }
          }
          _root.shroom = false;
        }
        for (e in _root.bomf[_root.lev]) {
          maxx = new flash.geom.Matrix();
          maxx.translate(_root.bomf[_root.lev][e][0], _root.bomf[_root.lev][e][1]);
          maxx.scale(hdx, hdx);
          splat.draw(crater, maxx);
        }
        savv = 0;
        if (_root.levsav[_root.lev] == undefined) {
          _root.levsav[_root.lev] = [];
        }
        if (_root.bomf[_root.lev] == undefined) {
          _root.bomf[_root.lev] = [];
        }
        if (_root.levblow[_root.lev] == undefined) {
          _root.levblow[_root.lev] = [];
        } else {
          for (e in _root.levblow[_root.lev]) {
            f1 = _root.levblow[_root.lev][e];
            levz[f1] = 0;
          }
        }
        player.xp = _root.playerx;
        player.yp = _root.playery;
        if (!nomore && _root.donelev[_root.lev] && _root.chesttype[_root.lev] != 4) {
          _root.m.nextFrame();
        }
        qq = _root._quality;
        if (qq != 'high') {
          _root._quality = 'high';
        }
        if (!error) {
          maxx = new flash.geom.Matrix();
          maxx.translate(b._x, b._y - bggg._y);
          maxx.scale(hdx, hdx);
          bgg.draw(b, maxx);
          f1 = 18;
          b.w1.gotoAndStop(f1);
          b.w2.gotoAndStop(f1);
          b.w3.gotoAndStop(f1);
          b.w4.gotoAndStop(f1);
          b.bg.gotoAndStop(f1);
          b._visible = false;
        }
        v1 = e + a;
        trg = createEmptyMovieClip('dblockx', 489);
        dblock = new flash.display.BitmapData(gridxs, gridys, true, 0);
        maxx = new flash.geom.Matrix();
        maxx.translate(0, 0);
        trg.attachBitmap(dblock, 1);
        trg._xscale = 100 / hdx;
        trg._yscale = trg._xscale;
        e = 0;
        while (e < levz.length) {
          if (levz[e] > 0 && levz[e] <= 1 or levz[e] == 1.9 or levz[e] == 1.94 or levz[e] == 1.93 or levz[e] == 3) {
            outgrid(e);
            if (levz[e] == 1.93 or levz[e] == 1.94) {
              if (levz[e] == 1.94) {
                webs[e] = random(3) + 1;
                tiles.gotoAndStop(158 + webs[e]);
              } else {
                if (_root.floorNum >= 7 && _root.floorNum != 9) {
                  tiles.gotoAndStop(70);
                } else {
                  tiles.gotoAndStop(21);
                }
              }
              levz[e] = 0.99;
            } else {
              if (levz[e] == 3) {
                v1 = [levz[e + 1] == 3, levz[e + rowz] == 3, levz[e - 1] == 3, levz[e - rowz] == 3];
                v2 = random(2) - 1;
                if (v1[0]) {
                  v2 = 1;
                }
                if (v1[1]) {
                  v2 = 2;
                }
                if (v1[2]) {
                  v2 = 3;
                }
                if (v1[3]) {
                  v2 = 4;
                }
                if (v1[2] && v1[0]) {
                  v2 = 5;
                }
                if (v1[3] && v1[1]) {
                  v2 = 6;
                }
                if (v1[0] && v1[1]) {
                  v2 = 7;
                }
                if (v1[1] && v1[2]) {
                  v2 = 8;
                }
                if (v1[2] && v1[3]) {
                  v2 = 9;
                }
                if (v1[3] && v1[0]) {
                  v2 = 10;
                }
                if (v1[0] && v1[1] && v1[2]) {
                  v2 = 11;
                }
                if (v1[1] && v1[2] && v1[3]) {
                  v2 = 12;
                }
                if (v1[2] && v1[3] && v1[0]) {
                  v2 = 13;
                }
                if (v1[3] && v1[0] && v1[1]) {
                  v2 = 14;
                }
                if (v1[0] && v1[1] && v1[2] && v1[3]) {
                  v2 = 15;
                }
                tiles.gotoAndStop(23 + v2);
              } else {
                if (levz[e] == 1.9) {
                  levz[e] = 1.8;
                  tiles.gotoAndStop(random(4) + 11);
                } else {
                  if (levz[e] == 1) {
                    if (_root.floorNum >= 7 && _root.floorNum != 9) {
                      tiles.gotoAndStop(80 + random(3));
                    } else {
                      if (_root.rarer[_root.lev] == e) {
                        tiles.gotoAndStop(15);
                      } else {
                        tiles.gotoAndStop(random(10) + 1);
                      }
                    }
                  } else {
                    tiles.gotoAndStop(94 + random(5) + _root.floorNum * 5);
                    levz[e] = 0;
                    clevc[e] = 0;
                  }
                }
              }
            }
            maxx = new flash.geom.Matrix();
            maxx.translate(xenf, yenf);
            maxx.scale(hdx, hdx);
            dblock.draw(tiles, maxx);
          }
          ++e;
        }
        yyo = 1;
        e = 0;
        while (e < levz.length) {
          switch (levz[e]) {
            case 4:
              turd('locktile', e);
              break;
            case 1.3:
              turd('egg', e);
              break;
            case 1.4:
              if (random(40) != 0 or beenHere) {
                turd('fireblock', e);
              } else {
              case 1.41:
                levz[e] = 1.4;
                turd('fireblock2', e);
                break;
              case 1.5:
                if (random(40) != 0 or beenHere) {
                  turd('breakblock', e);	//Poop
                } else {
                case 1.495:
                  if (random(20) != 0 or beenHere) {
                    trg = turd('breakblock3', e);	//Poop w/ Guardian
                    if (trg) {
                      if (levz[e] > 1) {
                        efly(trg);
                      }
                    }
                    trg.shit = true;
                  } else {
                  case 1.4955:
                    trg = turd('breakblock4', e);	//Golden Poop
                    trg.goldPoop = true;
                    break;
                  case 1.49:
                    levz[e] = 1.5;
                    turd('breakblock2', e);			//Flaming Poop
                  }
                }
              }
          }
          ++e;
        }
        if (qq != 'high') {
          _root._quality = qq;
        }
        e = 0;
        while (e < 700) {
          levz[ingrid(40 + e, 130)] = 1.9;
          e += 10;
        }
        e = 0;
        while (e < 700) {
          levz[ingrid(40 + e, 450)] = 1.9;
          e += 10;
        }
        e = 0;
        while (e < 300) {
          levz[ingrid(40, 130 + e)] = 1.9;
          e += 10;
        }
        e = 0;
        while (e < 300) {
          levz[ingrid(600, 130 + e)] = 1.9;
          e += 10;
        }
        e = 0;
        while (e < levz.length) {
          if (levz[e] < 0) {
            f1 = 9 - levz[e];
            if (!beenHere or f1 == 44.2 or f1 == 42.2 or f1 == 44.1 or f1 == 42.1 or f1 == 42) {
              outgrid(e);
              if (f1 < 10) {
                f1 = 5 - levz[e];
              }
              f2 = 1;
              if (Math.round(f1) == 62) {
                f2 = 7;
              }
              if (!_root.beenlev2[_root.lev] or f1 > 6) {
                i = 0;
                while (i < f2) {
                  create(xenf, yenf + 10 + i, 0, 0, 0, 0, f1);
                  ++i;
                }
              }
              levz[e] = 0;
            }
          }
          if (Math.abs(levz[e]) <= 0) {
            levz[e] = 0;
          }
          ++e;
        }
        if (beenHere) {
          e = 0;
          while (e < levz.length) {
            if (levz[e] < 0) {
              levz[e] = 0;
            }
            if (Math.abs(levz[e]) <= 0) {
              levz[e] = 0;
            }
            ++e;
          }
        }
        clevc = levz.slice(0, -1);
        e = 0;
        while (e < levz.length) {
          if (clevc[e] == 2 or clevc[e] == 0.99 or clevc[e] == 3.6) {
            clevc[e] = 0;
          }
          if (clevc[e] > 1 && clevc[e] < 2 or clevc[e] == 3) {
            clevc[e] = 1;
          }
          ++e;
        }
        e = 0;
        while (e < levz.length) {
          f2 = clevc[e] + ' ' + clevc[e + rowz + 1];
          f3 = clevc[e + 1] + ' ' + clevc[e + rowz];
          if (f2 == '0 0' && f3 == '1 1') {
            clevc[e] = 2;
            clevc[e + rowz + 1] = 2;
          }
          if (f2 == '1 1' && f3 == '0 0') {
            clevc[e + 1] = 2;
            clevc[e + rowz] = 2;
          }
          ++e;
        }
        for (e in clevc) {
          if (clevc[e] == 2) {
            clevc[e] = 1;
          }
        }
        e = 0;
        while (e < levz.length) {
          f2 = clevc[e] + ' ' + clevc[e + 1];
          f4 = levz[e] + ' ' + levz[e + 1];
          f3 = clevc[e] + ' ' + clevc[e + rowz];
          f5 = levz[e] + ' ' + levz[e + rowz];
          if (f2 == '1 1' && f4 == '0 0') {
            clevc[e] = 0;
            clevc[e + 1] = 0;
          }
          if (f3 == '1 1' && f5 == '0 0') {
            clevc[e + 1] = 0;
            clevc[e + rowz] = 0;
          }
          ++e;
        }
        if (_root.lev == _root.boner) {
          _root.treasd = true;
        }
        if (_root.lev == _root.boner2) {
          _root.treasd2 = true;
        }
        if (_root.lev == _root.sacrificeRoom) {
          _root.sacRoomRevealed = true;
        }
        for (e in door) {
          trg = door[e];
          trg.gotoAndStop(4);
          if (error) {
            trg._visible = false;
          } else {
            if (_root.lev == _root.bossRoom && !trg._visible && (Math.abs(e - _root.door) == 2 or e == _root.door or _root.door <= 0) && !sat) {
              sat = true;
              trg._visible = true;
              trg.gol = 166;
            } else {
              if (satan) {
                trg._visible = false;
                if ((Math.abs(e - _root.door) == 2 or _root.door <= 0) && !sat) {
                  sat = true;
                  trg.gol = _root.lastl;
                  if (trg.gol == 166 or trg.gol <= 0) {
                    trg.gol = 35;
                  }
                  trg._visible = true;
                }
              }
            }
          }
          if (trg._visible) {
            trg.blo = ingrid(trg._x, trg._y);
            _root.seenRoom[trg.gol] = true;
            if (haveEffect[91]) {
              if (trg.gol == _root.sacrificeRoom) {
                _root.sacRoomRevealed = true;
              }
              if (trg.gol == _root.boner) {
                _root.treasd = true;
              }
              if (trg.gol == _root.boner2) {
                _root.treasd2 = true;
              }
              if (trg.gol == _root.secretRoom) {
                revealSecretRoom();
              }
              if (trg.gol == _root.secretRoom2) {
                revealSecretRoom2();
              }
              if (trg.gol == _root.minibossRoom) {
                _root.minibossKnown = true;
              }
            }
            if (_root.lev == _root.secretRoom && (_root.lastl == undefined or _root.lastl == _root.lev) && trg.gol != _root.bossRoom && trg.gol != _root.bossRoom2) {
              _root.lastl = trg.gol;
            }
            if (trg.gol == _root.curseRoom or _root.lev == _root.curseRoom) {
              _root.seenCurseRoom = true;
              trg.cus = true;
              trg.gotoAndStop(36);
            } else {
              if (_root.lev == _root.secretRoom && (_root.lastl == trg.gol or haveEffect[76]) or haveEffect[76] && trg.gol == _root.secretRoom && _root.lev != _root.bossRoom2 && _root.lev != _root.bossRoom && _root.lev != _root.minibossRoom) {
                trg.hide = true;
                trg.gotoAndStop(17);
                levz[trg.blo] = 0;
              } else {
                if (_root.lev == _root.secretRoom2 && (_root.secretRoom != trg.gol or haveEffect[76]) or haveEffect[76] && trg.gol == _root.secretRoom2 && _root.lev != _root.bossRoom2 && _root.lev != _root.bossRoom && _root.lev != _root.minibossRoom) {
                  trg.hide2 = true;
                  trg.gotoAndStop(17);
                  levz[trg.blo] = 0;
                } else {
                  if ((trg.gol == _root.secretRoom or _root.lev == _root.secretRoom) && !satan) {
                    trg.hide = true;
                    trg.gotoAndStop(10);
                    levz[trg.blo] = 1.85;
                    if (trg.gol == _root.bossRoom or trg.gol == _root.bossRoom2 or _root.lev == _root.bossRoom or _root.lev == _root.bossRoom2 or _root.lev == _root.minibossRoom or _root.lev == _root.arenaRoom) {
                      levz[trg.blo] = 2;
                    }
                  } else {
                    if ((trg.gol == _root.secretRoom2 or _root.lev == _root.secretRoom2) && !satan) {
                      trg.hide2 = true;
                      trg.gotoAndStop(10);
                      levz[trg.blo] = 1.85;
                      if (trg.gol == _root.bossRoom or trg.gol == _root.bossRoom2 or _root.lev == _root.bossRoom or _root.lev == _root.bossRoom2 or _root.lev == _root.minibossRoom or _root.lev == _root.arenaRoom) {
                        levz[trg.blo] = 2;
                      }
                    } else {
                      if (satan or trg.gol == 166) {
                        trg.sat = true;
                        trg.gotoAndStop(12);
                      } else {
                        if (trg.gol == _root.bossRoom or _root.lev == _root.bossRoom or trg.gol == _root.bossRoom2 or _root.lev == _root.bossRoom2) {
                          trg.boss = true;
                          _root.bossd = true;
                          trg.gotoAndStop(16);
                        } else {
                          if (trg.gol == _root.arenaRoom or _root.lev == _root.arenaRoom) {
                            arenaActive = 1;
                            _root.chambb = true;
                            trg.arenaRoom = true;
                            trg.gotoAndStop(27);
                          } else {
                            if (trg.gol == _root.arcadeRoom) {
                              _root.seenArcade = true;
                              trg.arcadeRoom = true;
                              trg.gotoAndStop(20);
                            } else {
                              if (trg.gol == _root.boner2 or _root.lev == _root.boner2) {
                                _root.treasd2 = true;
                                trg.boner2 = true;
                                if (_root.treasureRoom2Opened) {
                                  trg.gotoAndStop(32);
                                } else {
                                  trg.gotoAndStop(30);
                                }
                              } else {
                                if (trg.gol == _root.boner or _root.lev == _root.boner) {
                                  _root.treasd = true;
                                  trg.boner = true;
                                  if (_root.treasureRoomOpened) {
                                    trg.gotoAndStop(32);
                                  } else {
                                    trg.gotoAndStop(30);
                                  }
                                } else {
                                  if (trg.gol == _root.shopl) {
                                    _root.shopaz = true;
                                    trg.shop = true;
                                    trg.gotoAndStop(9);
                                  } else {
                                    if (trg.gol == _root.libraryRoom) {
                                      _root.librarySeen = true;
                                      trg.lib = true;
                                      trg.gotoAndStop(9);
                                    } else {
                                      levz[trg.blo] = 1.85;
                                    }
                                  }
                                }
                              }
                            }
                          }
                        }
                      }
                    }
                  }
                }
              }
            }
            if (_root.floorNum == 11 && !trg.hide && !trg.hide2) {
              levz[trg.blo] = 2;
            }
          }
          f2 = 28;
          f1 = ((trg._rotation - 90) / 180) * Math.PI;
          trg.xp = trg._x - Math.sin(f1) * f2;
          trg.yp = trg._y + Math.cos(f1) * f2;
        }
        mapd();
        for (e in _root.levit[_root.lev]) {
          create(_root.levit[_root.lev][e][1], _root.levit[_root.lev][e][2], 0, 0, 0, 0, 5 + _root.levit[_root.lev][e][0] * 0.01);
        }
        if (gopill) {
          create(320, 240, 0, 0, 0, 0, 5.07); //this never comes into play, debug?
        }
        if (inem) {
          inl.gotoAndStop('empty');
          inl.swapDepths(33901);
        } else {
          gotoAndStop('empty');
        }
        lads.swapDepths(491);
        _root.beenlev2[_root.lev] = true;
      }

      function spawnb(f1, f2) {
        if (levz.length <= 1) {
          levz = new Array(200);
        }
        if (f1._alpha < 30) {
          if (f2 < -0.5 or f2 > 0) {
            f2 -= 0.2;
          }
        } else {
          if (f1._alpha < 75) {
            if (f2 == 1) {
              f2 = 1.9;
            } else {
              if (f2 < -0.5 or f2 > 0) {
                f2 -= 0.1;
              }
            }
          }
        }
        var v3 = ingrid(f1._x, f1._y);
        levz[v3] = f2;
      }

      function sideflip(f1, trg2) {
        trg.sf2 = trg2;
        if (trg2 == undefined) {
          if (trg.sf2 == undefined) {
            trg2 = trg.d;
          } else {
            trg2 = trg.sf2;
          }
        }
        trg.sf = true;
        if (f1 * trg2._xscale < -100) {
          trg2._xscale *= -1;
        }
      }

      function pathfind(trg, f1, f2, f3) {
        if (trg.speed == undefined) {
          trg.speed = 1;
        }
        if (trg.s == 35) {
          f3 *= 1.1;
        }
        if ((trg.xp != f1 or trg.yp != f2) && fra > 5) {
          v1 = ingrid(f1, f2);
          outgrid(v1);
          xpp = xenf;
          ypp = yenf;
          v2 = ingrid(trg.xp, trg.yp);
          outgrid(v2);
          xppp = xenf;
          yppp = yenf;
          if (v2 != trg.tiler) {
            --trg.tiletimer;
            if (trg.tiler == undefined or trg.tiletimer < 0 or trg == player) {
              trg.tiler = v2;
              trg.tiletimer = 2 / Math.max(0.2, f3);
            }
          }
          if (fra % 3 == 1) {
            v2 = 40 / enfget(trg.xbew, trg.ybew);
            v2 = levz[ingrid(trg.xp + trg.xbew * v2, trg.yp + trg.ybew * v2)];
            if (v2 > 0 && v2 < 1) {
              trg.speed = 0.7;
            } else {
              trg.speed = 1;
            }
          }
          v2 = trg.tiler;
          if (levz[trg.tiler] < 0.99 && trg.s != 16) {
            if (trg.s == 58) {
              levz[trg.tiler] = 0.2;
            } else {
              levz[trg.tiler] = 0.9;
            }
          }
          if (f3 == undefined) {
            f3 = 1;
          }
          f3 *= trg.speed;
          nogo = true;
          if ((fra + trg.e) % 10 == 1) {
            if (trg.see) {
              v5 = linecheckxx(xppp, yppp, xpp, ypp);
              trg.lastv = v5;
            } else {
              v5 = linecheck(xppp, yppp, xpp, ypp);
              trg.lastv = v5;
            }
            if (trg.lastv && trg.firss + 40 <= fra && random(3) == 0 && gochar) {
              trg.firss = fra;
              _root.soundy('Zombie_Walker_Kid.mp', 100);
            }
          } else {
            v5 = trg.lastv;
          }
          trg.d.h.stop();
          if (!trg.gonuts) {
            f3 *= 0.83;
          }
          if (trg.d.h._currentframe > 2) {
            f3 *= 1.2;
            trg.d.h.nextFrame();
          } else {
            if (trg.gonuts) {
              trg.d.h.gotoAndStop(2);
            }
          }
          if (v5 && enf or v1 == v2) {
            if (trg.gonuts) {
              trg.d.h.nextFrame();
              f3 *= 1.1;
            }
            trg.tiletimer -= 5;
            trg.gridtime -= 10;
            xenf = f1;
            yenf = f2;
            nogo = false;
          } else {
            if (levz[v1] != 1) {
              if ((trg.gridder == undefined or trg.gridtime < 0) && nogridyet) {
                nogridyet = false;
                trg.gridder = levz.slice(0, -1);
                acts = [];
                acts2 = [];
                z = -1;
                for (;;) {
                  if (!(z > -100 && trg.gridder[v2] >= 0)) break;
                  if (z == -1) {
                    pff(v1, -1);
                  } else {
                    for (e in acts) {
                      v1 = trg.gridder[acts[e]];
                      if (v1 < z) {
                        acts2.push(acts[e]);
                      } else {
                        outgrid(acts[e]);
                        pff(ingrid(xenf, yenf + roxx), v1);
                        pff(ingrid(xenf + roxx, yenf), v1);
                        pff(ingrid(xenf - roxx, yenf), v1);
                        pff(ingrid(xenf, yenf - roxx), v1);
                      }
                    }
                  }
                  acts2[acts2.length] = 0;
                  acts = acts2.slice(0, -1);
                  acts2 = [];
                  --z;
                }
                if (z < -99) {
                  trg.gridder = 0;
                }
                trg.gridtime = Math.min(20, -z) + ball.length * 2 + 7;
              }
              trg.gridtime * 0.9;
              trg.gridtime -= f3 * 3;
              if (trg.gridder != undefined && trg.gridder != 0) {
                outgrid(v2);
                v3 = -100;
                testarr = [ingrid(xenf + roxx, yenf), ingrid(xenf - roxx, yenf + roxx), ingrid(xenf - roxx, yenf), ingrid(xenf - roxx, yenf - roxx), ingrid(xenf, yenf - roxx), ingrid(xenf + roxx, yenf - roxx), ingrid(xenf, yenf + roxx), ingrid(xenf + roxx, yenf + roxx)];
                arrr = [0, 0, 0, 0, 0, 0, 0, 0];
                arrrr = [0, 0, 0, 0, 0, 0, 0, 0];
                for (e in testarr) {
                  if (levz[testarr[e]] != 0) {
                    arrr[e] = 1;
                  }
                }
                for (e in testarr) {
                  if (arrr[e] == 1) {
                    arrrr[e] = -1;
                    arrrr[e + 1] = -1;
                    arrrr[e - 1] = -1;
                    if (e == 0 or e == 7) {
                      arrrr[7] = -1;
                      arrrr[0] = -1;
                    }
                  }
                }
                for (e in testarr) {
                  if (clevc[testarr[e]] == 0) {
                    pff1(testarr[e], 0);
                  }
                }
                if (v3 < 0) {
                  outgrid(v4);
                  nogo = false;
                }
              }
            } else {}
          }
          if (!nogo && enf > 0.1) {
            var v6 = xenf - trg.xp;
            var v7 = yenf - trg.yp;
            xenf = v6;
            yenf = v7;
            enf = enfget(xenf, yenf);
            if (enf > 1) {
              enf = (Math.min(enf * 0.1, 2) / enf) * f3;
              trg.xbew *= 0.7;
              trg.ybew *= 0.7;
              trg.xbew += xenf * enf;
              trg.ybew += yenf * enf;
            }
          } else {
            yenf = 0;
            xenf = 0;
            trg.xbew *= 0.5;
            trg.ybew *= 0.5;
          }
        } else {
          yenf = 0;
          xenf = 0;
          trg.xbew *= 0.85;
          trg.ybew *= 0.85;
        }
        gochar = false;
      }

      function mhity(f1, f2) {
        if (f1 > 20 && f1 < 620 && f2 > 110 && f2 < 447) {
          f33 = ingrid(f1, f2);
          f1 = levz[f33];
          if (f1 >= 1 && f1 != 3) {
            return true;
          }
        } else {
          return true;
        }
      }

      function mhitx(f1, f2) {
        if (f1 > 20 && f1 < 620 && f2 > 110 && f2 < 447) {
          f1 = levz[ingrid(f1, f2)];
          if (f1 > 1.8 && f1 != 3) {
            return true;
          }
        } else {
          return true;
        }
      }

      function mhix() {
        f3 = false;
        for (i in hardx[v1]) {
          f3 = !f3;
          if (f3) {
            if (mhity(f1 + hardx[v1][i], f2 + hardy[v1][i])) {
              f5 += hardx[v1][i];
              f6 += hardy[v1][i];
            }
          }
        }
        f3 = true;
        if (Math.abs(f5) > 0 or Math.abs(f6) > 0 or trg.gh) {
          for (i in hardx[v1]) {
            f3 = !f3;
            if (f3) {
              if (mhity(f1 + hardx[v1][i], f2 + hardy[v1][i])) {
                f5 += hardx[v1][i];
                f6 += hardy[v1][i];
              }
            }
          }
        }
      }

      function shit(f1, f2) {
        return blorz.hitTest(f1 + _x, f2 + _y, true);
      }

      function mhit(f1, f2) {
        if (f1 > 20 && f1 < 620 && f2 > 110 && f2 < 447) {
          f1 = levz[ingrid(f1, f2)];
          if (f1 >= 1) {
            return true;
          }
        } else {
          return true;
        }
      }

      function pff3(f4) {
        f4 = levz[f4];
        if (f4 != 0.99) {
          if (f4 >= 1) {
            f5 = -1;
          } else {
            if (f4 > 0) {
              f5 -= 0.3;
            }
          }
        }
      }

      function pff3x1(f4) {
        f4 = levz[f4];
        if (f4 != 3) {
          if (f4 >= 1) {
            f5 = -1;
          } else {
            if (f4 > 0) {
              f5 -= 0.3;
            }
          }
        }
      }

      function linecheckxx(f1, f2, f3, f4) {
        var v5 = f1 - f3;
        var v6 = f2 - f4;
        var v7 = enfget(v5, v6);
        var v8 = 2.5;
        if (v7 > 0) {
          v5 /= v7;
          v6 /= v7;
          v5 *= 10;
          v6 *= 10;
          var v2 = 0;
          while (v2 < v7) {
            f1 -= v5;
            f2 -= v6;
            f3 = ingrid(f1, f2);
            if (levz[f3] >= 1.8 && levz[f3] != 1.85 && levz[f3] != 3) {
              v8 = -1;
            }
            v2 += 10;
          }
        }
        return v8 > 0;
      }

      function linecheckx(f1, f2, f3, f4) {
        var v5 = f1 - f3;
        var v6 = f2 - f4;
        var v4 = enfget(v5, v6);
        f5 = 2.5;
        f6 = 5;
        if (v4 > 0) {
          v5 /= v4;
          v6 /= v4;
          v5 *= 10;
          v6 *= 10;
          var v1 = 0;
          while (v1 < v4) {
            f1 -= v5;
            f2 -= v6;
            pff3(ingrid(f1, f2));
            v1 += 10;
          }
        }
        return f5 > 0;
      }

      function linecheck(f1, f2, f3, f4) {
        var v5 = f1 - f3;
        var v6 = f2 - f4;
        var v4 = enfget(v5, v6);
        f5 = 2.5;
        f6 = 5;
        if (v4 > 0) {
          v5 /= v4;
          v6 /= v4;
          v5 *= 10;
          v6 *= 10;
          var v3 = 0;
          while (v3 < v4) {
            f1 -= v5;
            f2 -= v6;
            pff3(ingrid(f1 + f6, f2 + f6));
            pff3(ingrid(f1 - f6, f2 + f6));
            pff3(ingrid(f1 - f6, f2 - f6));
            pff3(ingrid(f1 + f6, f2 - f6));
            v3 += 10;
          }
        }
        return f5 > 0;
      }

      function linechecky(f1, f2, f3, f4) {
        var v5 = f1 - f3;
        var v6 = f2 - f4;
        var v4 = enfget(v5, v6);
        f5 = 2.5;
        f6 = 2;
        if (v4 > 0) {
          v5 /= v4;
          v6 /= v4;
          v5 *= 10;
          v6 *= 10;
          var v3 = 0;
          while (v3 < v4) {
            f1 -= v5;
            f2 -= v6;
            pff3x1(ingrid(f1 + f6, f2 + f6));
            pff3x1(ingrid(f1 - f6, f2 + f6));
            pff3x1(ingrid(f1 - f6, f2 - f6));
            pff3x1(ingrid(f1 + f6, f2 - f6));
            v3 += 10;
          }
        }
        return f5 > 0;
      }

      function displayBannerMessage(f1) {
        _root.hud.st1.tex = f1;
        _root.hud.st1.gotoAndPlay(1);
        _root.hud.st1._visible = true;
      }

      function spacebarIDToItemID(f1) {
        if (f1 >= 18 or f1 == 16) {
          return 40;
        } else {
          return 32;
        }
      }

      function itemIDToSpacebarID(f1) {
        if (f1 < 55) {
          return 32;
        } else {
          return 40;
        }
      }

      function powerlevel() {
        _root.beenlev[_root.lev] = 2;
        var v3 = _root.faceMode;
        if (!highs.empty) {
          if (fra - lastcraf > 30) {
            lastcraf = fra;
            if (_root.lev == 35 && _root.floorNum == 1 && fra < 15) {
            } else {
              if (highs.it == 12 or highs.it == 11 or highs.it == 71) {
                _root.soundy('1up.wav');
              } else {
                if (highs.it == 92) {
                  _root.soundy('band aid pick up.wav', 50);
                } else {
                  if (_root.lev == _root.bossRoom or _root.lev == _root.minibossRoom) {
                    _root.soundy('Powerup2.mp', 50);
                  } else {
                    if (_root.lev == _root.boner or _root.lev == _root.boner2) {
                      _root.soundy('Powerup1.mp', 50);
                    } else {
                      if (_root.lev == _root.shopl) {
                        _root.soundy('Powerup3.mp', 50);
                      } else {
                        _root.soundy('Choir_unlock.wav', 50);
                      }
                    }
                  }
                }
              }
            }
          }
        }
        maxp = true;
        if (!highs.empty && fra - lastcra >= 30) {
          if (arenaActive == 1 && _root.lev == _root.arenaRoom) {
            arenaActive = 2;
          }
          displayBannerMessage(_root.itemNames[highs.it]);
          displayCornerMessage(_root.itemDescriptions[highs.it]);
          if (highs.d._currentframe == 10) {
            var v2 = highs.d.d;
          } else {
            var v2 = highs.d;
          }
          highs.empty = true;
          for (i in _root.Library) {
            if (highs.it == _root.Library[i]) {
              _root.carryingBook = true;
            }
          }
          if (highs.it == 22 or highs.it == 23 or highs.it == 24 or highs.it == 25 or highs.it == 26) {
            ++player.hp;
          } else {
            if (highs.it == 12 or highs.it == 15 or highs.it == 16) {
              player.hp = 1000;
              if (highs.it == 15) {
                hat(25);
              }
            }
          }
          ++_root.pickedUp[highs.it];
          if (!challengeItem) {
            _root.collectedItem[highs.it] = true;
          }
          if (highs != player) {
            highs.d.d.d.gotoAndPlay(21);
          }
          player.d.gotoAndStop(4);
          player.it = highs.it;
          if (highs.it == 7) {
            _root.faceMode = 8;
            hat(7);
          } else {
            if (highs.it < 8) {
              _root.faceMode = 1 + highs.it;
              _root.headMode = _root.faceMode;
            }
          }
          if (highs.it == 27) {
            hat(27);
          }
          if (highs.it == 81) {
            if (_root.characterID == 4) {
              _root.armor = 1;
            } else {
              _root.pickedUp[23] += 1 - player.mhp;
            }
            haveEffect[23] = _root.pickedUp[23];
          }
          if (highs.it == 52) {
            _root.RegularDropPool.push(125, 125, 125, 125, 125, 125, 106, 106, 106, 106, 106, 106);
          }
          if (highs.it == 179) {
            giveEternalHeart();
          }
          if (highs.it == 137) {
            if (_root.pickedUp[137] == 1) {
              _root.bombs += 5;
            }
          } else {
            if (highs.it == 189) {
              _root.headMode = 42;
              _root.bodyMode = 27;
              ++player.hp;
            } else {
              if (highs.it == 190) {
                hat(58);
                _root.bombs = 99;
              } else {
                if (highs.it == 191) {
                  _root.headMode = 44;
                } else {
                  if (highs.it == 193) {
                    hat(55);
                    ++player.hp;
                  } else {
                    if (highs.it == 194) {
                      itemSpawnsPickups = [5.3];
                      hat(60);
                    } else {
                      if (highs.it == 195) {
                        itemSpawnsPickups = [5.07, 5.07, 5.07, 5.07];
                        hat(59);
                      } else {
                        if (highs.it == 196) {
                          hat(56);
                          itemSpawnsPickups = [5.010000003, 5.010000003];
                        } else {
                          if (highs.it == 197) {
                            hat(57);
                          } else {
                            if (highs.it == 198) {
                              _root.bodyMode = 26;
                              itemSpawnsPickups = [5.35, 5.07, 5.02, 5.010000003, 5.3, 5.03, 5.04];
                            } else {
                              if (highs.it == 182) {
                                haveEffect[3] = 1;
                                _root.pickedUp[3] = 1;
                                _root.headMode = 41;
                                ++_root.armor;
                                player.hp += 15;
                              } else {
                                if (highs.it == 183) {
                                  hat(53);
                                } else {
                                  if (highs.it == 180) {
                                    _root.bodyMode = 24;
                                  } else {
                                    if (highs.it == 149) {
                                      if (!haveEffect[2]) {
                                        _root.pickedUp[2] = 0.5;
                                        haveEffect[2] = 0.5;
                                      }
                                    } else {
                                      if (highs.it == 168) {
                                        hat(50);
                                      } else {
                                        if (highs.it == 139) {
                                          _root.bodyMode = 20;
                                        } else {
                                          if (highs.it == 169) {
                                            _root.headMode = 40;
                                            if (!haveEffect[2]) {
                                              _root.pickedUp[2] = 0.3;
                                              haveEffect[2] = 0.3;
                                            }
                                            _root.faceMode = 20;
                                          } else {
                                            if (highs.it == 155) {
                                              hat(47);
                                            } else {
                                              if (highs.it == 156) {
                                                hat(48);
                                              } else {
                                                if (highs.it == 161) {
                                                  hat(49);
                                                } else {
                                                  if (highs.it == 153) {
                                                    hat(46);
                                                    if (!haveEffect[2]) {
                                                      _root.pickedUp[2] = 0.4;
                                                      haveEffect[2] = 0.4;
                                                    }
                                                    _root.faceMode = 23;
                                                  } else {
                                                    if (highs.it == 165) {
                                                      hat(51);
                                                    } else {
                                                      if (highs.it == 176) {
                                                        hat(52);
                                                        player.hp += 1.5;
                                                      } else {
                                                        if (highs.it == 154) {
                                                          _root.headMode = 38;
                                                        } else {
                                                          if (highs.it == 143) {
                                                            _root.headMode = 35;
                                                          } else {
                                                            if (highs.it == 159) {
                                                              _root.sk = 7;
                                                              sk = 7;
                                                              _root.headMode = 39;
                                                              _root.bodyMode = 22;
                                                              haveEffect[115] = 1;
                                                              _root.pickedUp[115] = 1;
                                                            } else {
                                                              if (highs.it == 157) {
                                                                hat(41);
                                                              } else {
                                                                if (highs.it == 150) {
                                                                  _root.faceMode = 24;
                                                                  hat(44);
                                                                } else {
                                                                  if (highs.it == 151) {
                                                                    _root.headMode = 37;
                                                                    _root.faceMode = 21;
                                                                  } else {
                                                                    if (highs.it == 148) {
                                                                      _root.bodyMode = 21;
                                                                      pillTintPlayer(40, 100, 40);
                                                                    } else {
                                                                      if (highs.it == 138) {
                                                                        hat(42);
                                                                        ++player.hp;
                                                                      } else {
                                                                        if (highs.it == 140) {
                                                                          _root.headMode = 34;
                                                                          _root.bombs += 5;
                                                                        } else {
                                                                          if (highs.it == 141) {
                                                                            hat(43);
                                                                            pageantBoyCoins = 7;
                                                                          } else {
                                                                            if (highs.it == 125) {
                                                                              _root.bombs += 5;
                                                                            } else {
                                                                              if (highs.it == 134) {
                                                                                _root.bodyMode = 19;
                                                                              } else {
                                                                                if (highs.it == 118) {
                                                                                  _root.sk = 7;
                                                                                  sk = 7;
                                                                                } else {
                                                                                  if (highs.it == 114) {
                                                                                    _root.bodyMode = 15;
                                                                                  } else {
                                                                                    if (highs.it == 122) {
                                                                                      haveEffect[122] = false;
                                                                                    } else {
                                                                                      if (highs.it == 116) {
                                                                                        _root.itemCharges = 1;
                                                                                        hat(36);
                                                                                      } else {
                                                                                        if (highs.it == 132) {
                                                                                          hat(39);
                                                                                        } else {
                                                                                          if (highs.it == 119) {
                                                                                            player.hp += 5;
                                                                                            hat(35);
                                                                                          } else {
                                                                                            if (highs.it == 129) {
                                                                                              player.hp += 0.5;
                                                                                              _root.bodyMode = 14;
                                                                                            } else {
                                                                                              if (highs.it == 115 or highs.it == 185) {
                                                                                                _root.headMode = 32;
                                                                                                haveEffect[115] = 1;
                                                                                                _root.pickedUp[115] = 1;
                                                                                                _root.faceMode = 18;
                                                                                              } else {
                                                                                                if (highs.it == 110) {
                                                                                                  hat(33);
                                                                                                } else {
                                                                                                  if (highs.it == 109) {
                                                                                                    hat(34);
                                                                                                  } else {
                                                                                                    if (highs.it == 103) {
                                                                                                      _root.headMode = 26;
                                                                                                      _root.faceMode = 15;
                                                                                                    } else {
                                                                                                      if (highs.it == 104) {
                                                                                                        _root.faceMode = 16;
                                                                                                        hat(32);
                                                                                                      } else {
                                                                                                        if (highs.it == 106) {
                                                                                                          _root.headMode = 9;
                                                                                                          _root.bombs += 5;
                                                                                                        } else {
                                                                                                          if (highs.it == 101) {
                                                                                                            ++player.hp;
                                                                                                            hat(29);
                                                                                                          } else {
                                                                                                            if (highs.it == 59) {
                                                                                                              _root.headMode = 24;
                                                                                                            } else {
                                                                                                              if (highs.it == 29) {
                                                                                                                _root.bodyMode = 10;
                                                                                                              } else {
                                                                                                                if (highs.it == 46) {
                                                                                                                  _root.bodyMode = 11;
                                                                                                                } else {
                                                                                                                  if (highs.it == 64) {
                                                                                                                    hat(26);
                                                                                                                  } else {
                                                                                                                    if (highs.it == 63) {
                                                                                                                      hat(24);
                                                                                                                    } else {
                                                                                                                      if (highs.it == 92) {
                                                                                                                        _root.armor += 2;
                                                                                                                        ++player.hp;
                                                                                                                        hat(23);
                                                                                                                      } else {
                                                                                                                        if (highs.it == 86) {
                                                                                                                        } else {
                                                                                                                          if (highs.it == 87) {
                                                                                                                            hat(22);
                                                                                                                          } else {
                                                                                                                            if (highs.it == 88) {
                                                                                                                            } else {
                                                                                                                              if (highs.it == 89) {
                                                                                                                                hat(20);
                                                                                                                                _root.faceMode = 14;
                                                                                                                              } else {
                                                                                                                                if (highs.it == 90) {
                                                                                                                                  hat(21);
                                                                                                                                } else {
                                                                                                                                  if (highs.it == 91) {
                                                                                                                                    hat(19);
                                                                                                                                  } else {
                                                                                                                                    if (highs.it == 81) {
                                                                                                                                      _root.pickedUp[81] = 8;
                                                                                                                                      haveEffect[81] = 8;
                                                                                                                                      _root.catlives = 1;
                                                                                                                                    } else {
                                                                                                                                      if (highs.it == 82) {
                                                                                                                                        _root.headMode = 22;
                                                                                                                                        _root.sk = 7;
                                                                                                                                        sk = 7;
                                                                                                                                      } else {
                                                                                                                                        if (highs.it == 72) {
                                                                                                                                          _root.armor += 3;
                                                                                                                                          _root.ShopItem.push(33, 33, 33, 33, 33, 33, 33);
                                                                                                                                          _root.bodyMode = 6;
                                                                                                                                        } else {
                                                                                                                                          if (highs.it == 79) {
                                                                                                                                            _root.armor += 1;
                                                                                                                                            hat(17);
                                                                                                                                          } else {
                                                                                                                                            if (highs.it == 80) {
                                                                                                                                              _root.armor += 2;
                                                                                                                                              _root.bodyMode = 8;
                                                                                                                                              _root.headMode = 20;
                                                                                                                                              _root.sk = 7;
                                                                                                                                              sk = 7;
                                                                                                                                            } else {
                                                                                                                                              if (highs.it == 20) {
                                                                                                                                                _root.bodyMode = 3;
                                                                                                                                              } else {
                                                                                                                                                if (highs.it == 13) {
                                                                                                                                                  _root.bodyMode = 4;
                                                                                                                                                  _root.headMode = 12;
                                                                                                                                                } else {
                                                                                                                                                  if (highs.it == 14) {
                                                                                                                                                    _root.headMode = 11;
                                                                                                                                                  } else {
                                                                                                                                                    if (highs.it == 59) {
                                                                                                                                                      _root.faceMode = 11;
                                                                                                                                                    } else {
                                                                                                                                                      if (highs.it == 31) {
                                                                                                                                                        _root.headMode = 13;
                                                                                                                                                      } else {
                                                                                                                                                        if (highs.it == 30) {
                                                                                                                                                          _root.bodyMode = 5;
                                                                                                                                                        } else {
                                                                                                                                                          if (highs.it == 21 or highs.it == 54) {
                                                                                                                                                            mapd();
                                                                                                                                                          } else {
                                                                                                                                                            if (highs.it == 9) {
                                                                                                                                                              hat(9);
                                                                                                                                                            } else {
                                                                                                                                                              if (highs.it == 69) {
                                                                                                                                                                _root.headMode = 17;
                                                                                                                                                              } else {
                                                                                                                                                                if (highs.it == 55) {
                                                                                                                                                                  _root.headMode = 18;
                                                                                                                                                                } else {
                                                                                                                                                                  if (highs.it == 76) {
                                                                                                                                                                    hat(13);
                                                                                                                                                                  } else {
                                                                                                                                                                    if (highs.it == 75) {
                                                                                                                                                                      player.hp += 2;
                                                                                                                                                                      hat(15);
                                                                                                                                                                    } else {
                                                                                                                                                                      if (highs.it == 32) {
                                                                                                                                                                        hat(16);
                                                                                                                                                                      } else {
                                                                                                                                                                        if (highs.it == 28) {
                                                                                                                                                                          _root.bodyMode = 7;
                                                                                                                                                                        }
                                                                                                                                                                      }
                                                                                                                                                                    }
                                                                                                                                                                  }
                                                                                                                                                                }
                                                                                                                                                              }
                                                                                                                                                            }
                                                                                                                                                          }
                                                                                                                                                        }
                                                                                                                                                      }
                                                                                                                                                    }
                                                                                                                                                  }
                                                                                                                                                }
                                                                                                                                              }
                                                                                                                                            }
                                                                                                                                          }
                                                                                                                                        }
                                                                                                                                      }
                                                                                                                                    }
                                                                                                                                  }
                                                                                                                                }
                                                                                                                              }
                                                                                                                            }
                                                                                                                          }
                                                                                                                        }
                                                                                                                      }
                                                                                                                    }
                                                                                                                  }
                                                                                                                }
                                                                                                              }
                                                                                                            }
                                                                                                          }
                                                                                                        }
                                                                                                      }
                                                                                                    }
                                                                                                  }
                                                                                                }
                                                                                              }
                                                                                            }
                                                                                          }
                                                                                        }
                                                                                      }
                                                                                    }
                                                                                  }
                                                                                }
                                                                              }
                                                                            }
                                                                          }
                                                                        }
                                                                      }
                                                                    }
                                                                  }
                                                                }
                                                              }
                                                            }
                                                          }
                                                        }
                                                      }
                                                    }
                                                  }
                                                }
                                              }
                                            }
                                          }
                                        }
                                      }
                                    }
                                  }
                                }
                              }
                            }
                          }
                        }
                      }
                    }
                  }
                }
              }
            }
          }
          if (highs.it == 48) {
            _root.faceMode = 10;
          }
          if (highs.it >= 33 && highs.it != 46 && highs.it != 48 && highs.it < 50 or highs.it == 56 or highs.it == 58 or highs.it == 65 or highs.it == 66 or highs.it == 77 or highs.it == 78 or highs.it == 83 or highs.it == 84 or highs.it == 85 or highs.it == 86 or highs.it == 93 or highs.it == 97 or highs.it == 102 or highs.it == 105 or highs.it == 107 or highs.it == 111 or highs.it == 123 or highs.it == 124 or highs.it == 126 or highs.it == 127 or highs.it == 130 or highs.it == 133 or highs.it == 135 or highs.it == 136 or highs.it == 137 or highs.it == 145 or highs.it == 146 or highs.it == 147 or highs.it == 158 or highs.it == 164 or highs.it == 160 or highs.it == 166 or highs.it == 171 or highs.it == 175 or highs.it == 177 or highs.it == 181 or highs.it == 186 or highs.it == 192 or highs.it == 177) {
            _root.pickedUp[highs.it] = 1;
            itb = 15;
            _root.hud.it.gotoAndStop(8);
            _root.colit = highs.it;
            _root.itemChargeTable[_root.spacebarItem] = _root.itemCharges;
            if (_root.spacebarItem > 0) {
              if (_root.spacebarItem == 90) {
                player.flyby = false;
              }
              highs.d.gotoAndStop(10);
              v2 = highs.d.d;
              v2.d.gotoAndPlay(1);
              f11 = _root.spacebarItem + spacebarIDToItemID(_root.spacebarItem);
              v2.d.d.gotoAndStop(f1);
              _root.spacebarItem = highs.it - itemIDToSpacebarID(highs.it);
              highs.it = f11;
              highs.empty = false;
              highs.done = false;
              highs.dones = false;
              highs.d.d.d.d.gotoAndStop(highs.it);
            } else {
              _root.spacebarItem = highs.it - itemIDToSpacebarID(highs.it);
            }
            if (_root.spacebarItem != 11) {
              _root.itemCharges = _root.itemChargeTable[_root.spacebarItem];
              if (haveEffect[116]) {
                _root.itemCharges = Math.max(0.334, _root.itemCharges);
              }
            }
          } else {
            if (highs.d._currentframe != 10 && highs.s == 5) {
              highs.d.gotoAndStop(11);
            }
            _root.collectionScreen.push(highs.it);
            if (!notUpgrade(highs.it) && !satan) {
              if (highs.it == 5) {
                _root.upgradeCounter += 0.2;
              } else {
                ++_root.upgradeCounter;
              }
            }
          }
          if (highs.it >= 50 && highs.it < 54) {
            hat(highs.it - 48);
          } else {
            switch (highs.it) {
              case 19:
                _root.bombs += 10;
                hat(30);
                break;
              case 17:
                _root.keys = 99;
                hat(14);
                break;
              case 18:
                _root.coins = 99;
                break;
              case 74:
                _root.coins += 25;
            }
          }
          if (highs.it == 48) {
            hat(6);
          }
          if (highs.it == 70) {
            hat(8);
          }
          if (highs.it == 62) {
            _root.headMode = 15;
          }
          if (highs.it == 69) {
            _root.faceMode = 13;
          }
          lastcra = fra;
          if (highs != player) {
            if (highs.d._currentframe == 10) {
              highs.dones = false;
            } else {
              highs.done = true;
            }
          }
          if (_root.pickedUp[4] + _root.pickedUp[38] + _root.pickedUp[42] + Math.max(0, _root.pickedUp[81]) >= 1.1) {
            _root.SecretUnlocked[40] = true;
          }
          if (_root.pickedUp[13] + _root.pickedUp[14] + _root.pickedUp[70] >= 2) {
            _root.SecretUnlocked[37] = true;
          }
          if (_root.pickedUp[55] && _root.pickedUp[31] + _root.pickedUp[30] + _root.pickedUp[39] + _root.pickedUp[41] >= 1) {
            _root.SecretUnlocked[47] = true;
          }
        } else {
          highs.dones = false;
        }
        nohit = false;
        if (_root.faceMode != v3) {
        }
        haveEffect[highs.it] = _root.pickedUp[highs.it];
      }

      function invp() {
        player._visible = false;
        for (e in ball) {
          trg2 = ball[e];
          if (trg2.s <= 3) {
            trg2._visible = false;
          }
        }
      }

      function displayCornerMessage(f1) {
        if (f1 != 0) {
          _root.st2._visible = f1 != 0;
          _root.st2.gotoAndPlay(1);
          _root.st2.tex = f1;
          f1 = f1.split('');
          _root.st2._x = 620 - f1.length * 10;
        }
      }

      function frez(trg) {
        if (trg.frezz < 0 or !trg.frezz) {
          trg.frezz = 70;
          trg.uncol = Math.round(fra + trg.freez + 1);
          specialColoring(trg);
        }
      }

      function spida(f1, trg) {
        if (f1) {
          colorit(trg, 0.5, 0.5, 0.5, -100, -100, -100);
          trg.spida = 2;
        } else {
          colorit(trg, 0.5, 0.5, 0.5, 150, 150, 150);
          trg.spida = 1;
        }
        if (f1 == undefined) {
          trg.spid = 120;
        } else {
          trg.spid = 60;
        }
        trg.uncol = Math.round(fra + trg.spid);
      }

      function spidcol(trg) {
        if (haveEffect[110] && !lows.ba && random(5) == 0 && !trg.mom && trg.s != 84) {
          if (trg.mag) {
            for (z in trg.mags) {
              frez(trg.mags[z]);
            }
          }
          if (trg.worm == 6) {
            for (z in worm) {
              frez(worm[z]);
            }
          } else {
            if (!trg.worm) {
              frez(trg);
            }
          }
          if (trg.s == 19) {
            trg2 = trg;
            while (trg2.trg2) {
              trg2 = trg2.trg2;
              frez(trg2);
            }
            trg2 = trg;
            while (trg2.trg3) {
              trg2 = trg2.trg3;
              frez(trg2);
            }
          }
        }
        if (haveEffect[151] or catMode) {
          if (!lows.ba && random(6) == 0 or catMode && blueFlies < 1 && ball.length < 30 && (random(3) == 0 or !haveEffect[152])) {
            ++blueFlies;
            blueFlyTarget = trg;
          }
        }
        if (haveEffect[103] && !lows.ba && random(4) == 0 or lows.trinketTears == 1) {
          if (trg.poisonDuration > 20) {
            trg.poisonDuration += 40;
          } else {
            trg.poisonDuration = 60;
          }
          if (lows.trinketTears == 1) {
            trg.poisonDamage = 4;
          } else {
            trg.poisonDamage = 2;
          }
          trg.uncol = Math.round(fra + 60);
          specialColoring(trg);
        }
        if (haveEffect[89] && random(4) == 0 or lows.ba == 3 && random(2) == 0) {
          spida(lows.ba == 3, trg);
        }
      }

      function giveEternalHeart() {
        _root.soundy('superholy.wav', 100);
        _root.eternalHeart = !_root.eternalHeart;
        if (!_root.eternalHeart) {
          ++player.hp;
          ++haveEffect[22];
          _root.over.gotoAndStop(16);
          _root.pickedUp[22] = haveEffect[22];
        }
      }

      function dropTrinket() {
        if (_root.TrinketPool.length > 0) {
          if (dropPolaroid) {
            dropPolaroid = false;
            return 47; //Polaroid
          } else {
            if (trg.goldPoop) {
              return 52; //Counterfeit Penny
            } else {
              f1 = random(_root.TrinketPool.length);
              var v2 = _root.TrinketPool[f1] * 1;
              _root.TrinketPool.splice(f1, 1);
              return v2;
            }
          }
        } else {
          return dropTarotCard();
        }
      }

      function dropTarotCard() {
        if (random(5) != 0) {
          return random(22) + 7; //Tarot Cards
        } else {
          return random(5) + 70; //Playing Cards
        }
      }

      function givePillItem(trg) {
        var v3 = false;
        if (trg > 7) {
          f2 = trg;
        } else {
          if (trg == 4) {
            f2 = random(6) + 1;
          } else {
            if (trg == 3) {
              f2 = dropTarotCard();
            } else {
              f2 = trg.col;
            }
          }
        }
        player.pillItem = pillColor(f2);
        f1 = _root.pillItem > 0;
        f3 = f2 > 28 && f2 < 69;
        if (f3) {
          if (!haveTrinket(f2) && (!haveTrinket(53) or haveEffect[139])) {
            f1 = ['Fish Head', 'Pinky Eye', 'Push Pin', 'Liberty Cap', 'Umbilical Cord', 'Childs Heart', 'Curved Horn', 'Rusted Key', 'Goat Hoof', 'Moms Pearl', 'Cancer', 'Red Patch', 'Match Stick', 'Lucky Toe', 'Cursed Skull', 'Safety Cap', 'Ace of Spades', 'Isaacs Fork', 'The Polaroid', 'A Missing Page', 'Bloody Penny', 'Burnt Penny', 'Flat Penny', 'Counterfeit Penny', 'Tick', 'Isaacs Head', 'Maggys Faith', 'Judas\' Tongue', '???\'s Soul', 'Samsons Lock', 'Cains Eye', 'Eves Bird Foot', 'The Left Hand'];
            f1 = f1[Math.max(0, f2 - 29)];
            displayBannerMessage(f1);
            _root.atrixer = _root.trinket1;
            _root.trinket1 = f1;
            _root.soundy('shellgame' + random(2) + '.wav');
            if (haveEffect[139]) {
              f1 = _root.trinketSlot2 > 0;
            } else {
              f1 = _root.trinketSlot1 > 0;
            }
            if (f2 == 53) {
              hat(61);
            }
          } else {
            v3 = true;
            trg.dones = false;
            trg.fra = fra + 10;
          }
        } else {
          if (f2 < 7) {
            displayBannerMessage('Pills here!');
            _root.soundy('shellgame' + random(2) + '.wav');
            _root.collectedItem[43] = true;
          } else {
            _root.collectedItem[61] = true;
            tarotText(f2);
            _root.soundy('Book Page Turn 12.wav', 100);
          }
        }
        if (!v3) {
          if (f1) {
            if (!f3) {
              f1 = _root.pillItem;
              _root.pillItem = f2;
            } else {
              if (!haveEffect[139]) {
                f1 = _root.trinketSlot1;
                _root.trinketSlot1 = f2;
              } else {
                f1 = _root.trinketSlot2;
                _root.trinketSlot2 = _root.trinketSlot1;
                _root.trinketSlot1 = f2;
              }
            }
            if (trg == 3 or trg == 4) {
              trg = spaw(player.xp, player.yp, 0, 5.3);
            }
            trg.d.gotoAndStop(7);
            trg.col = f1;
            trg.dones = false;
            trg.done = false;
            trg.fra = fra + 10;
            trg.d.d.gotoAndStop(3);
            if (highs.yp > 0) {
              trg.ybew -= -Math.min(player.yp - highs.yp, 0) * 0.5;
            }
          } else {
            if (trg == 3 or trg == 4) {
              pilll = true;
            } else {}
            if (f3) {
              if (haveEffect[139]) {
                _root.trinketSlot2 = _root.trinketSlot1;
              }
              _root.trinketSlot1 = f2;
            } else {
              _root.pillItem = f2;
            }
            trg.d.d.gotoAndStop(2);
          }
          if (_root.trinketSlot2 == 53) {
            _root.trinketSlot2 = _root.trinketSlot1;
            _root.trinketSlot1 = 53;
            _root.atrixer = _root.trinket1;
            _root.trinket1 = 'Tick';
          }
          if (!f3) {
            _root.hud.pilll.gotoAndStop(2);
          } else {
            _root.hud.plix.gotoAndStop(2);
          }
          player.d.gotoAndStop(4);
          player.it = 43;
        }
      }

      function collectCoin(trg) {
        if (trg.col == 1) {
          _root.soundy('pennypickup.mp');
          return 1;
        } else {
          if (trg.col == 2) {
            displayCornerMessage('a Nickel');
            _root.soundy('nickelpickup.mp');
            return 5;
          } else {
            displayCornerMessage('a Dime');
            _root.soundy('dimepickup.wav');
            return 10;
          }
        }
      }

      function donateBlood(f1) {
        if (_root.floorNum > 6 && player.hp < 1 && _root.armor > 0 && player.mhp > 0) {
          _root.armor -= 0.5;
          player.hp += 0.5;
        }
        if (player.hp > 0.5 or _root.armor <= 0) {
          f11 = _root.armor;
          _root.armor = 0;
          playerhurt(0.5, 201, f11 > 0);
          _root.armor = f11;
        } else {
          playerhurt(0.5, 201);
        }
        ++_root.so.data.bloodDonations;
        if (_root.so.data.bloodDonations > 20) {
          _root.SecretUnlocked[36] = true;
        }
        if (!f1) {
          _root.soundy('bloodbank touched.wav', 90);
        }
      }

      function greedDamage() {
        if (lasth - fra < 0 && player._visible && telf == undefined && playsave < 0 && unic < 0 && player._currentframe != 6 && horse <= 0 && decoy <= 0) {
          loseCoins = true;
        }
      }

      function balljunk() {
        if ((lows.s == 14 or lows.s == 18) && highs.s == 36) {
          nohit = true;
          lows.xbew += xenf * 0.01;
          lows.ybew += yenf * 0.01;
        }
        if (highs.s == 4) {
          if (lows.fly or lows.ang or lows.meat < 3) {
            nohit = true;
          }
        }
        if (lows.s == 30 && highs.s == 30) {
          highs.dones = true;
          nohit = true;
        }
        if (lows.s == 30 && highs.s == 36) {
          nohit = true;
        }
        if (lows.fly or lows.meat or lows.bird or lows.charge or lows.ang) {
          switch (highs.s) {
              if (highs.s !== 18) {
              } else {
              case 9:
              case 13:
              case 14:
                highs.dones = true;
              }
          }
        } else {
          if (lows == player && !nohit) {
            dodo = false;
            switch (highs.s) {
              case 53:
                nohit = true;
                break;
              case 33:
                nohit = true;
              case 31:
              case 32:
              case 24:
              case 28:
              case 45:
              case 46:
              case 47:
              case 48:
              case 49:
              case 50:
              case 52:
              case 68:
              case 57:
              case 62:
              case 63:
              case 64:
              case 65:
              case 66:
              case 69:
              case 71:
              case 74:
              case 75:
              case 76:
              case 55:
              case 58:
              case 59:
              case 57:
              case 81:
              case 82:
              case 83:
              case 84:
                if (freez <= 0) {
                  dodo = true;
                }
                if (highs.s == 62 && altboss) {
                  dodo = false;
                }
                if (highs.s == 62 && highs.dy < -30) {
                  nohit = true;
                } else {
                case 10:
                case 11:
                case 12:
                case 15:
                case 17:
                case 18:
                case 19:
                case 20:
                case 21:
                case 25:
                case 23:
                case 26:
                case 29:
                case 34:
                case 35:
                case 36:
                case 26.5:
                case 38:
                case 39:
                case 40:
                case 41:
                case 43:
                case 44:
                case 51:
                case 54:
                case 56:
                case 60:
                case 61:
                case 67:
                case 72:
                case 73:
                case 75:
                case 76:
                case 77:
                case 79:
                case 80:
                case 96:
                case 86:
                case 85:
                case 94:
                case 87:
                case 88:
                case 93:
                case 89:
                case 97:
                case 98:
                case 99:
                case 100:
                case 101:
                case 102:
                  if (highs.s == 86 or highs.s == 50 or highs.s == 90) {
                    greedDamage();
                  }
                  if (highs.s == 9 && highs.belial) {
                    dodo = true;
                  }
                  if (highs.s == 85 or highs.s == 94) {
                    highs.ypp = undefined;
                    highs.xpp = highs.ypp;
                    highs.xbew *= 0.6;
                    highs.ybew *= 0.6;
                  }
                  if (highs.s == 99) {
                    pub = true;
                  }
                  dodo = dodo or highs.champion or trg.specoz == 7 or trg.specoz == 2;
                  if (freez <= 0 && horse <= 0) {
                    if (dodo) {
                      playerhurt(1, highs.s);
                    } else {
                      playerhurt(0.5, highs.s);
                    }
                  }
                  if (highs.sss == 100 or highs.sss == 101 && altboss) {
                    playslow = 20;
                  }
                  if (highs.die) {
                    highs.dones = true;
                  }
                case 13:
                case 14:
                case 27:
                case 30:
                case 16:
                  if ((haveEffect[13] or unic > 0 or demon > 0 or horse > 0) && highs.aidsdone <= fra) {
                    highs.aidsdone = fra + 30;
                    if (horse > 0) {
                      nohit = true;
                    }
                    if (haveEffect[13]) {
                      highs.poisonDuration = 60;
                      highs.poisonDamage = 3.5;
                      hurt(highs, 30);
                    } else {
                      hurt(highs, 40);
                    }
                  }
                }
            }
          }
        }
        if (highs.s == 4) {
          if (fra - highs.lfra < 4) {
            nohit = true;
            highs.lfra = fra;
          } else {
            highs.xbew += lows.xbew * 0.4;
            highs.ybew += lows.ybew * 0.4;
          }
        }
        if (lows.s == 4 && highs.s != 62) {
          if (!lows.flir) {
            lows.xbew *= 0.5;
            lows.ybew *= 0.5;
          }
          highs.xbew *= 0.2;
          highs.ybew *= 0.2;
          if (highs.s == 85 or highs.s == 94) {
            highs.dones = true;
          }
        }
        if (highs.s == 44 && lows.s != 44) {	//Poky stabs everyone.
          if (highs.s != 69) {
            hurt(lows, 20);
          }
        }
        if (highs.s == 66 && highs.horse && lows.s != 66) {
          hurt(lows, 20);
        }
        if (highs.s == 45 && lows.s != 45 && fra - lows.fra > 10) {
          hurt(lows, 20);
        }
        if (lows.s == 44 && highs.s != 44) {	//Eveyone gets stabbed by Poky.
          hurt(highs, 20);
        }
        if (highs.s == 63 && highs.d._currentframe == 7) {
          hurt(lows, 20);
        }
        if (highs.s == 99 && highs.d._currentframe > 7) {
          if (lows.s == 14 or lows.s == 85) {
            hurt(lows, 20);
          }
        }
        if (highs.s == 28 && highs.mags[1].mode == 2) {
          if (lows.s == 23 or lows.s == 85) {
            hurt(lows, 20);
          }
          if (highs.mag == 1 && lows.s == 4) {
            _root.soundy('SMB_large_chews_4.wav');
            lows.done = true;
            highs.mode = 4;
            highs.bomb = 0;
            nohit = true;
          }
        }
        if (lows == player && highs.s == 5 && !highs.dones) {
          if (_root.keys >= 1 or _root.goldenKey or highs.d._currentframe != 6) {
            nohit = true;
            if (highs.d._currentframe < 7 && (highs.col != 3 && highs.col != 5 or highs.d._currentframe != 4)) {
              if (highs.c2) {
                highs.d.d.gotoAndStop(6);
              } else {
                highs.d.d.gotoAndStop(2);
              }
            }
            highs.dones = true;
            switch (highs.d._currentframe) {
              case 34:
                if (_root.floorNum == 9 && _root.altchap && haveTrinket(47)) {
                  if (beamer <= 0) {
                    beamer = 1;
                    _root.floorNum = 11;
                  }
                } else {
                  if (_root.heaven && _root.floorNum != 11) {
                    if (beamer <= 0) {
                      _root.heaven = 2;
                      beamer = 1;
                    }
                  } else {
                    _root.levz = undefined;
                    moveon();
                    _root.door = undefined;
                    if (_root.floorNum == 11) {
                      f1 = 24;
                    } else {
                      if (_root.floorNum == 9 && _root.altchap) {
                        f1 = 23;
                      } else {
                        f1 = Math.min(9 + _root.so.data.momKills, 21);
                        if (f1 == 20) {
                          f1 = 21;
                        }
                        if (_root.floorNum == 9) {
                          f1 = 22;
                        }
                      }
                    }
                    _root.gotoAndStop(f1);
                    highs.dones = false;
                    nohit = false;
                  }
                }
                break;
              case 1:	//Heart
                if (highs.col == 4) {
                  giveEternalHeart();
                } else {
                  if (highs.col == 3) {
                    ++_root.armor;
                  } else {
                    if (player.hp < player.mhp) {
                      if (highs.col != 2) {
                        ++player.hp;
                        red = 7;
                      } else {
                        player.hp += 0.5;
                        red = 5;
                      }
                    } else {
                      nohit = false;
                      highs.dones = false;
                      highs.d.d.gotoAndStop(1);
                    }
                  }
                }
                if (highs.col == 4) {
                  _root.soundy('superholy.wav', 100);
                } else {
                  if (highs.col == 3) {
                    _root.soundy('Holy.mp', 100);
                  } else {
                    if (nohit) {
                      _root.soundy('boss2_bubbles' + random(2) + '.wav', 100);
                    }
                  }
                }
                break;
              case 2:	//Coin
                _root.coins += collectCoin(highs);
                if (haveTrinket(49) && random(2) == 0) {
                  itemSpawnsPickups.push(5.010000002);
                }
                if (haveTrinket(50) && random(2) == 0) {
                  itemSpawnsPickups.push(5.040000001);
                }
                if (haveTrinket(51) && random(2) == 0) {
                  itemSpawnsPickups.push(5.03);
                }
                if (haveTrinket(52) && random(2) == 0) {
                  ++_root.coins;
                }
                break;
              case 3:	//Key
                if (highs.col == 2) {
                  _root.goldenKey = true;
                  _root.soundy('goldenkey.wav', 100);
                } else {
                  ++_root.keys;
                  _root.soundy('KeyPickup_Gauntlet.wav', 85);
                }
                break;
              case 4:	//Bomb
                if (highs.col == 3 or highs.col == 5) {
                  nohit = false;
                  highs.dones = false;
                  if (!highs.troll) {
                    highs.troll = true;
                    displayCornerMessage('Trolololol');
                  }
                } else {
                  if (highs.col != 2) {
                    ++_root.bombs;
                  } else {
                    _root.bombs += 2;
                    displayCornerMessage('1 + 1 free');
                  }
                }
                if (nohit) {
                  _root.soundy('fetus_feet' + random(2) + '.wav', 100);
                }
                break;
              case 5:	//Chest
                if (!highs.empty && chestopen == undefined) {
                  _root.soundy('Chest_Open.mp', 100);
                  chestopen = highs;
                }
                nohit = false;
                highs.dones = false;
                break;
              case 6:	//Locked Chest
                if ((_root.keys >= 1 or _root.goldenKey) && !highs.empty && chestopen == undefined) {
                  _root.soundy('Unlock00.wav', 100);
                  if (!_root.goldenKey) {
                    --_root.keys;
                  }
                  chestopen = highs;
                  _root.soundy('Chest_Open.mp', 100);
                }
                nohit = false;
                highs.dones = false;
                break;
              case 7:	//Pill
                if (fra - highs.fra > 0) {
                  givePillItem(highs);
                } else {
                  highs.dones = false;
                  highs.fra = fra + 10;
                }
                break;
              case 8:	//Machine
                if (highs.col == 31) {	//Demon Beggar
                  if (!highs.spin && !highs.busted) {
                    donateBlood();
                    highs.d.d.gotoAndStop(37);
                    highs.spin = true;
                    lastspin = fra + 100;
                    highs.wtf = false;
                  }
                } else {
                  if (highs.col == 1) {
                    if (!highs.spin && !highs.busted) {	//Blood Donation Machine
                      donateBlood();
                      highs.d.d.gotoAndStop(33);
                      highs.d.d.d.gotoAndPlay(1);
                      highs.spin = true;
                      lastspin = fra + 100;
                      highs.wtf = false;
                    }
                  } else {
                    if (highs.col == 10) {
                      if (highs.spin && highs.d.d.d._currentframe > 110) {
                        if (Math.abs(xenf) < 13) {
                          highs.d.d.gotoAndStop(44);
                        } else {
                          if (highs.xp > lows.xp) {
                            highs.d.d.gotoAndStop(43);
                          } else {
                            highs.d.d.gotoAndStop(45);
                          }
                        }
                        highs.wtf = false;
                        lastspin = fra + 15;
                      }
                    }
                    if (_root.coins >= 1 && !highs.spin && !highs.busted && (highs.col != 10 or highs.yp - lows.yp < 0)) {
                      --_root.coins;
                      if (highs.col == 10) {	//Shell Game
                        highs.d.d.gotoAndStop(42);
                        highs.shellGuyItem = random(4);
                        if (random(13) == 0 && !haveEffect[9]) {
                          highs.shellGuyItem = 5;
                        }
                      } else {
                        if (highs.col > 1 && highs.col < 10) {
                          highs.d.d.gotoAndStop(37);
                        } else {
                          _root.soundy('Coin_Slot.mp', 100);
                          highs.d.d.gotoAndStop(2);
                        }
                      }
                      highs.spin = true;
                      lastspin = fra + 100;
                    }
                  }
                }
                highs.dones = false;
                nohit = false;
                break;
              case 9:	//Trap Door
                if (highs.d.d._currentframe > 10 && highs.d.d._currentframe < 24 && highs.open) {
                  player._visible = false;
                  plxxx = highs.xp;
                  plyyx = highs.yp;
                  highs.d.d.gotoAndPlay(25);
                }
                highs.dones = false;
                break;
              case 15: //Shop Item
                f1 = [0, 3, 5, 5, 15, 2, 3, 3, 7, 1, 2, 3, 5, 5, 0, 0, 3, 3];
                f1 = f1[highs.d.d._currentframe];
                if (_root.coins >= f1 && !satan or satan && (_root.armor >= 3 or highs.d.d._currentframe != 11)) {
                  if (satan) {
                    ++_root.devilDeals;
                    if (_root.devilDeals > 1) {
                      _root.SecretUnlocked[54] = true;
                    }
                    if (f1 == 3) {
                      lasth = -100;
                      if (_root.armor >= 3) {
                        playerhurt(3, 200);
                      } else {
                        playerhurt(3, 200);
                      }
                    } else {
                      _root.pickedUp[22] -= f1;
                      haveEffect[22] = _root.pickedUp[22];
                      lasth = -100;
                      f11 = _root.armor;
                      f2 = f1 - player.mhp + player.hp;
                      player.mhp -= f1;
                      playerhurt(Math.max(0, f2), 200, f11 > 0);
                      if (player.mhp > 0 or f11 > 0 && player.mhp >= 0) {
                        _root.armor = f11;
                      } else {
                        f11 = 0;
                        _root.armor = 0;
                        playerhurt(10, 200);
                      }
                    }
                    _root.mmus = _root.soundy('isaacsatanitemget.mp', 100);
                    plffff = player.d._currentframe;
                  } else {
                    _root.coins -= f1;
                  }
                  highs.done = true;
                  switch (highs.d.d._currentframe) { //Shop Pickups
                    case 12:	//Key - 5 Cents
                    case 16:	//Key on Sale - 3 Cents
                      ++_root.keys;
                      _root.soundy('KeyPickup_Gauntlet.wav', 85);
                      player.d.gotoAndStop(4);
                      player.it = 202;
                      break;
                    case 13:	//Soul Heart - 5 Cents
                    case 17:	//Soul Heart on Sale - 3 Cents
                      ++_root.armor;
                      _root.soundy('Holy.mp', 100);
                      player.d.gotoAndStop(4);
                      player.it = 203;
                      break;
                    case 1:		//Heart - 3 Cents
                    case 5:		//Heart on Sale - 2 Cents
                      _root.soundy('boss2_bubbles' + random(2) + '.wav', 100);
                      ++player.hp;
                      player.d.gotoAndStop(4);
                      player.it = 200;
                      break;
                    case 3:		//Pill - 5 Cents
                    case 7:		//Pill on Sale - 3 Cents
                      givePillItem(highs);
                      break;
                    case 2:		//Bomb - 5 Cents
                    case 6:		//Bomb on Sale - 3 Cents
                      ++_root.bombs;
                      _root.soundy('fetus_feet' + random(2) + '.wav', 100);
                      player.d.gotoAndStop(4);
                      player.it = 201;
                      break;
                    case 4:		//Item - 15 Cents
                    case 8:		//Item on Sale - 7 Cents
                    case 9:		//Devil Item - 1 Heart Container
                    case 10:	//Devil Item - 2 Heart Containers
                    case 11:	//Devil Item - 3 Soul Hearts
                      powerlevel();
                  }
                  if (satan && player.hp <= 0) {
                    player.d.gotoAndStop(plffff);
                  }
                } else {
                  highs.dones = false;
                }
                break;
              case 10:	//Treasure
                powerlevel();
            }
          }
        }
      }

      function ballhit(e, a) {
        trg = ball[e];
        trg2 = ball[a];
        if (trg.s != 2 or trg2.s != 2) {
          f1 = Math.max(e, a);
          f2 = Math.min(e, a);
          if (tests.getPixel(f1, f2) == 0) {
            tests.setPixel(f1, f2, 1);
            nohit = false;
            if (trg.s > trg2.s) {
              lows = trg2;
              highs = trg;
            } else {
              lows = trg;
              highs = trg2;
            }
            if (highs.s == 28 && lows.s == 28) {
              nohit = true;
            }
            if (lows.s == 5 && highs.s != 5) {
              nohit = true;
            }
            if (highs.s < 4) {
              nohit = true;
            }
            if (highs.s == 5 && lows != player) {
              nohit = true;
            }
            if (lows.s == 9 or highs.s == 9 && (lows != player && !lows.fly && !lows.meat && !lows.ang && !lows.bird or lows.ni)) {
              nohit = true;
            }
            if (lows.outway or highs.outway && lows != player && lows.s != 2 && !lows.damger) {
              nohit = true;
            }
            if (lows.s == 44 && highs.outway or highs.s == 44 && lows.outway) {
              nohit = false;
            }
            if (lows.s == 44 && highs.s == 69) {
              nohit = true;
            }
            if (trg.fra == fra or trg2.fra == fra) {
              nohit = true;
            }
            if (lows.bird && highs.s == 4) {
              nohit = true;
            }
            if (highs.flir or lows.flir) {
              nohit = true;
            }
            if (!nohit && !trg.dones && !trg2.dones) {
              xenf = trg2.xp - trg.xp;
              siz = sizes[Math.round(trg.s)] + sizes[Math.round(trg2.s)];
              siz2 = siz;
              if (highs.s == 5 && (highs.col == 10 && highs.d._currentframe == 8 or highs.d._currentframe == 34)) {
                if (highs.d._currentframe == 34) {
                  siz2 += 17;
                } else {
                  siz2 += 28;
                }
                siz = siz2;
              }
              if (Math.abs(xenf) < siz) {
                yenf = trg2.yp - trg.yp;
                if (Math.abs(yenf) < siz) {
                  enf = xenf * xenf + yenf * yenf;
                  if (enf > 0 && enf < siz * siz) {
                    balljunk();
                    if (!nohit) {
                      v6 = lows.damger;
                      if (lows.s == 2 or v6) {
                        if (lows.charge) {
                          nohit = true;
                        }
                        nohit = highs.s == 23 or highs.s == 41 or highs.s == 32 or highs.s == 25 or highs.s == 55 or highs.s == 62;
                        if (lows.meat > 2) {
                          nohit = false;
                        }
                        if (!lows.hh[highs.e]) {
                          lows.hh[highs.e] = true;
                          v1 = lows.dmg;
                          if (lows.d._yscale == 135.5) {
                            v1 += 25;
                          }
                          if (highs.s == 41 && !haveEffect[48]) {
                            if (highs.d.hx.h._currentframe == 1 && lows.ybew < 0) {
                              v1 = 0;
                            }
                            if (highs.d.hx.h._currentframe == 2 && lows.xbew < 0) {
                              v1 = 0;
                            }
                            if (highs.d.hx.h._currentframe == 3 && lows.ybew > 0) {
                              v1 = 0;
                            }
                            if (highs.d.hx.h._currentframe == 4 && lows.xbew > 0) {
                              v1 = 0;
                            }
                          }
                          if (highs.s == 97 && !haveEffect[48]) {
                            if (highs.d._currentframe == 1 && lows.ybew < 0) {
                              v1 = 0;
                            }
                            if (highs.d._currentframe == 6 && lows.xbew > 0) {
                              v1 = 0;
                            }
                            if (highs.d._currentframe == 5 && lows.ybew > 0) {
                              v1 = 0;
                            }
                            if (highs.d._currentframe == 7 && lows.xbew < 0) {
                              v1 = 0;
                            }
                          }
                          hurt(highs, v1);
                          if (lows.s == 2) {
                            spidcol(highs);
                          }
                          if (highs.hp < 0 && lows.hairball && _root.hairball < 6 && random(_root.hairball) == 0) {
                            lows.d.gotoAndStop(149);
                            lows.d.d.gotoAndStop(1);
                            ++_root.hairball;
                          }
                        }
                        if (haveEffect[48] && !lows.ba or lows.ics or v6 or lows.knife or lows.trinketTears == 2) {
                          nohit = true;
                        } else {
                          if (haveEffect[169] && !lows.ba && lows.dmg > 10 && highs.hp < -6) {
                            lows.dmg *= 0.5;
                            lows.d._xscale *= 0.75;
                            lows.d._yscale *= 0.75;
                            nohit = true;
                          } else {
                            lows.dones = true;
                            lows.xp += lows.xbew * 0.8;
                            lows.yp += lows.ybew * 0.8;
                          }
                        }
                        if (lows.blueFlies && random(2) == 1) {
                          lows.dones = true;
                          lows.d = lows.d.d;
                        }
                        if (highs.s == 91) {
                          nohit = true;
                        }
                      } else {
                        if (highs.s != 28 && (lows != player or highs.s != 41 && highs.s != 23)) {
                          trg.gh = 2;
                          trg2.gh = 2;
                        }
                      }
                      if (!nohit) {
                        if (highs.s == 9 && lows == player) {
                          highs.dones = true;
                          if (highs.sss == 50 or highs.sss == 86 or highs.sss == 90) {
                            greedDamage();
                          }
                          if (highs.d._xscale > 115) {
                            playerhurt(1, highs.sss);
                          } else {
                            playerhurt(0.5, highs.sss);
                          }
                        }
                        v = trg.ma / (trg.ma + trg2.ma);
                        vv = 1 - v;
                        enf = Math.sqrt(enf);
                        f1 = (siz - enf) / enf;
                        trg.xp -= xenf * vv * f1;
                        trg.yp -= yenf * vv * f1;
                        trg2.xp += xenf * v * f1;
                        trg2.yp += yenf * v * f1;
                        xbewenf = trg2.xbew - trg.xbew;
                        ybewenf = trg2.ybew - trg.ybew;
                        bewenf = xbewenf * xbewenf + ybewenf * ybewenf;
                        if (bewenf > 0) {
                          bewenf = Math.sqrt(bewenf);
                        } else {
                          bewenf = 0;
                        }
                        enf = bewenf / enf;
                        if (bewenf > 2.5) {
                          soundy('bh');
                        }
                        if (maxp) {
                          enf += 0.5;
                        }
                        xenf *= enf;
                        yenf *= enf;
                        trg.xb -= xenf * vv;
                        trg.yb -= yenf * vv;
                        trg2.xb += xenf * v;
                        trg2.yb += yenf * v;
                        if (maxp) {
                          highs.xb *= 0.5;
                          highs.yb *= 0.5;
                        }
                        if (lows.s == 2 && (highs.s == 18 or highs.s == 14)) {
                          highs.xbew *= 0.5;
                          highs.ybew *= 0.5;
                          highs.xbew += lows.xbew * 0.5;
                          highs.ybew += lows.ybew * 0.5;
                        }
                        if (pub) {
                          f1 = trg;
                          trg = player;
                          if (bord()) {
                          }
                          trg = f1;
                          pub = false;
                        }
                      }
                    }
                  }
                }
              }
            }
          }
        }
        maxp = false;
      }

      function nextcha() {
        newstart(false);
      }

      function pull(f1, f2, f3, f4, f5) {
        if (f1 == 0) {
          v = 0.8;
        } else {
          v = 1.2;
        }
        v = 1;
        f1 = ball[f1];
        f2 = ball[f2];
        f5 = leg[f5];
        f5._x = f1._x;
        f5._y = f1._y;
        xenf = f1._x - f2._x;
        yenf = f1._y - f2._y;
        f5._rotation = (Math.atan(-xenf / yenf) / Math.PI) * 180 + 90;
        if (yenf >= 0) {
          f5._rotation += 180;
        }
        enf = Math.sqrt(xenf * xenf + yenf * yenf);
        f5._xscale = enf;
        f5._yscale = 50;
        xenf = f1._x + f1.xbew - f2._x - f2.xbew;
        yenf = f1._y + f1.ybew - f2._y - f2.ybew;
        enf = Math.sqrt(xenf * xenf + yenf * yenf);
        if (enf != 0) {
          enf = (f3 - enf) / enf;
          xenf *= enf * f4;
          yenf *= enf * f4;
          f1.xbew += xenf * v;
          f1.ybew += yenf * v;
          f2.xbew -= xenf / v;
          f2.ybew -= yenf / v;
        }
      }

      function trgnextd(trg2, f2) {
        if (trg2 == undefined) {
          trg2 = trg.d.d;
        }
        if (!trg.free or slow <= 0 or fra % 2 == 0) {
          trg2.nextFrame();
        }
        if (trg2._currentframe == trg2._totalframes) {
          var v2 = trg2._parent._currentframe;
          if (!f2) {
            trg2._parent.gotoAndStop(1);
          }
          return v2;
        }
      }

      function walkframe(f1) {
        trg.wf = true;
        if (f1 <= 0) {
          f1 = 1;
        }
        if (trg.d._currentframe < 3) {
          if (enfget(trg.xbew, trg.ybew) * f1 > 2) {
            trg.d.gotoAndStop(2);
          } else {
            trg.d.gotoAndStop(1);
          }
        }
      }

      function randrunc() {
        trg.randd = fra;
        if (trg.xpp == undefined) {
          trg.d.gotoAndStop(1);
          if (trg.wait++ > 13) {
            if (enfcheck(trg.xp, trg.yp, player.xp, player.yp, 100 + random(100)) && linecheckx(player.xp, player.yp, trg.xp, trg.yp)) {
              trg.xpp = player.xp + player.xbew * 5;
              trg.ypp = player.yp + player.ybew * 5;
            } else {
              f1 = 70 + random(40);
              f1 = trg.xp + crand(f1);
              f2 = trg.yp + crand();
              f1 = Math.min(540, Math.max(120, f1));
              f2 = Math.min(360, Math.max(210, f2));
              f3 = ingrid(f1, f2);
              if (levz[f3] < 1) {
                f4 = linecheck(f1, f2, trg.xp, trg.yp);
                if (!f4 && random(20) == 0) {
                  f4 = linecheckx(f1 * 0.9 + trg.xp * 0.1, f2 * 0.9 + trg.yp * 0.1, f1 * 0.1 + trg.xp * 0.9, f2 * 0.1 + trg.yp * 0.9);
                }
                if (f4) {
                  trg.xpp = f1;
                  trg.ypp = f2;
                  trg.wait = 15;
                }
              }
            }
          }
        }
        if (trg.xpp != undefined) {
          --trg.wait;
          trg.d.gotoAndStop(2);
          xenf = trg.xp - trg.xpp;
          yenf = trg.yp - trg.ypp;
          enf = enfget(xenf, yenf);
          if (enf < 14 or enfget(trg.xbew, trg.ybew) < 3 && trg.wait < 0) {
            trg.mode = 1;
            trg.xpp = undefined;
            trg.wait = 0;
          }
          enf = 6 / enf;
          trg.xbew -= xenf * enf;
          trg.ybew -= yenf * enf;
          sideflip(-xenf);
        }
        trg.xbew *= 0.6;
        trg.ybew *= 0.6;
      }

      function randrun() {
        trg.randd = fra;
        if (trg.xpp == undefined) {
          f1 = 40;
          if (trg.s == 68) {
            f1 = 80;
          }
          f1 = trg.xp + crand(f1);
          f2 = trg.yp + crand();
          if (trg.s == 68) {
            f1 = Math.min(540, Math.max(120, f1));
            f2 = Math.min(360, Math.max(210, f2));
          }
          f1 = ingrid(f1, f2);
          if (levz[f1] < 1) {
            outgrid(f1);
            trg.xpp = xenf;
            trg.ypp = yenf;
          }
        }
        if (trg.xpp != undefined) {
          if (trg.s != 64 && (trg.s != 66 or trg.d._currentframe < 7) && trg.s != 77 && trg.s != 76 && trg.s != 79) {
            trg.d.gotoAndStop(2);
          }
          xenf = trg.xp - trg.xpp;
          yenf = trg.yp - trg.ypp;
          enf = enfget(xenf, yenf);
          if (enf < 3 or enfget(trg.xbew, trg.ybew) < 0.2 && random(10) == 0) {
            trg.mode = 1;
            trg.xpp = undefined;
          }
          enf = 0.5 / enf;
          trg.xbew -= xenf * enf;
          trg.ybew -= yenf * enf;
          if (trg.s != 68) {
            sideflip(-xenf);
          }
        }
      }

      function randruny() {
        if (trg.d.d._currentframe == 19) {
          _root.soundy('Meat_impacts_' + random(3) + '.wav');
        }
        if (trg.xpp == undefined) {
          if (trg.s == 86) {
            trgnextd();
            firemode(180, 20, true);
          }
          if ((trg.s != 86 or trg.d._currentframe < 3) && (trg.alter != 2 or trg.wait++ > 15)) {
            trg.d.d.gotoAndStop(1);
            if (trg.alter == 2) {
              f1 = random(50) + random(70);
            } else {
              if (trg.s == 54) {
                f1 = random(50);
              } else {
                f1 = 0;
              }
            }
            trg.f1 = f1;
            if (enfcheck(trg.xp, trg.yp, player.xp, player.yp, 130 + f1 * 1.3)) {
              f2 = player.yp - yenf * f1 / 200;
              f1 = player.xp - xenf * f1 / 200;
              if (trg.s == 54) {
                f1 += player.xbew * 5;
                f2 += player.ybew * 5;
              }
            } else {
              f1 = trg.xp + crand(95 + f1);
              f2 = trg.yp + crand();
            }
            f1 = Math.min(620, Math.max(20, f1));
            f2 = Math.min(447, Math.max(110, f2));
            f1 = ingrid(f1, f2);
            if (levz[f1] < 1) {
              outgrid(f1);
              trg.xpp = xenf;
              trg.ypp = yenf;
            }
          }
        }
        if (trg.xpp != undefined) {
          trg.wait = 0;
          trg.d.gotoAndStop(2);
          trg.d.d.nextFrame();
          xenf = trg.xp - trg.xpp;
          yenf = trg.yp - trg.ypp;
          enf = enfget(xenf, yenf);
          if (trg.s == 54) {
            f1 = trg.d.d._currentframe - enf * 0.6;
          } else {
            f1 = trg.d.d._currentframe - enf * 0.3;
          }
          if (trg.d.d._currentframe < 5) {
            xenf *= 0.1;
            yenf *= 0.1;
          } else {
            if (f1 > 30) {
              trg.d.d.prevFrame();
              if (f1 > 45) {
                trg.d.d.prevFrame();
              }
            }
          }
          if (enf < 10 or enfget(trg.xbew + trg.ybew) < 0.75 && random(10) == 0) {
            if (trg.d.d._currentframe == trg.d.d._totalframes) {
              trg.xpp = undefined;
            }
          }
          enf = Math.min(3 + trg.f1 * 0.075, enf * 0.1) / enf;
          if (trg.f1) {
            f1 = 1 - trg.f1 / 500;
            trg.xbew *= f1;
            trg.ybew *= f1;
          }
          trg.xbew -= xenf * enf;
          trg.ybew -= yenf * enf;
          if (Math.abs(xenf) > 8) {
            sideflip(-xenf);
          }
        }
      }

      function markhere(trg) {
        var v2 = ingrid(trg.xp, trg.yp);
        if (trg != undefined) {
          trg.til = v2;
        }
        if (trg.mags.length < 2 or trg.s == 28) {
          if (levz[v2] < 0.99) {
            levz[v2] = 0.9;
          }
        }
      }

      function borderliner(f0) {
        if (f0 == undefined) {
          f0 = 1;
        }
        f9 = [0, 1, 1, 0, 0, -1, -1, 0, 0, 1];
        if (trg.dir == undefined) {
          trg.dir = 0;
          f2 = 0;
          while (f2 < 4) {
            ++f2;
            f1 = trg.dir * 2;
            f3 = ingrid(trg.xp + f9[f1] * roxx, trg.yp + f9[f1 + 1] * roxx);
            if (levz[f3] < 0.95) {
              ++trg.dir;
            } else {
              f2 = 10;
            }
          }
          if (f2 != 10) {
            trg.dir = random(4);
          }
        }
        trg.xbew *= 0.6;
        trg.ybew *= 0.6;
        if (trg.xpp == undefined) {
          f1 = trg.dir * 2;
          f3 = ingrid(trg.xp + (-f9[f1] - f9[f1 + 1]) * roxx, trg.yp + (-f9[f1 + 1] + f9[f1]) * roxx, true);
          f4 = ingrid(trg.xp - f9[f1 + 1] * roxx, trg.yp + f9[f1] * roxx, true);
          if (levz[f3] > 0.95 && levz[f4] < 0.95 && !trg.lastdd) {
            --trg.dir;
            trg.lastdd = true;
          } else {
            f3 = ingrid(trg.xp + f9[f1] * roxx, trg.yp + f9[f1 + 1] * roxx);
            if (levz[f3] < 0.9) {
              outgrid(f3);
              trg.xpp = xenf;
              trg.ypp = yenf;
              trg.lastdd = false;
            } else {
              ++trg.dir;
            }
          }
        }
        if (trg.dir > 3) {
          trg.dir -= 4;
        }
        if (trg.dir < 0) {
          trg.dir += 4;
        }
        if (trg.xpp != undefined) {
          enfcheck(trg.xp, trg.yp, trg.xpp, trg.ypp, 1000);
          if (enf < 5) {
            trg.xpp = undefined;
          }
          enf = f0 / enf;
          trg.xbew -= xenf * enf;
          trg.ybew -= yenf * enf;
          if (trg.xpp != undefined) {
            if (Math.abs(xenf) < Math.abs(yenf)) {
              trg.xbew *= 0.6;
              trg.xbew += (trg.xpp - trg.xp) * 0.4;
              xenf = 0;
            } else {
              trg.ybew *= 0.6;
              trg.ybew += (trg.ypp - trg.yp) * 0.4;
              yenf = 0;
            }
          }
        }
      }

      function newxx() {
        f9 = [0, 1, 1, 0, 0, -1, -1, 0];
        f10 = 0;
        var v1 = trg.s == 41 or trg.s == 44 or trg.s == 93 or trg.s == 97;
        for (;;) {
          if (!(trg.xpp == undefined && f10++ < 10)) break;
          f8 = [];
          a = 0;
          while (a < 4) {
            xenf = f9[a * 2] * roxx;
            yenf = f9[a * 2 + 1] * roxx;
            f4 = random(12);
            f1 = trg.xp + xenf * f4;
            f2 = trg.yp + yenf * f4;
            if (f1 > 620 or f1 < 20) {
              f1 = false;
            }
            if (f2 > 447 or f2 < 110) {
              f1 = false;
            }
            if (f1) {
              i = 1;
              while (i < f4) {
                f1 = trg.xp + xenf * i;
                f2 = trg.yp + yenf * i;
                f3 = ingrid(f1, f2);
                if (levz[f3] > 0.3 && (f10 < 9 or levz[f3] > 1)) {
                  --i;
                  break;
                }
                ++i;
              }
              f1 = trg.xp + xenf * i + yenf;
              f2 = trg.yp + yenf * i - xenf;
              f3 = ingrid(f1, f2, true);
              f1 = trg.xp + xenf * i - yenf;
              f2 = trg.yp + yenf * i + xenf;
              f4 = ingrid(f1, f2, true);
              if (levz[f3] < 0.2 or levz[f4] < 0.2 or random(10) == 0) {
                f8[a] = i;
              }
            } else {
              f8[a] = 0;
            }
            ++a;
          }
          f7 = 1.8;
          if (v1 && random(10) != 0) {
            f7 = 0.8;
          }
          f6 = -1;
          for (a in f8) {
            if (f8[a] > f7 && f1) {
              f7 = f8[a];
              f6 = a;
            }
          }
          if (f7 < 2 && random(10) == 0) {
            f6 = -1;
          }
          f1 = Math.abs(trg.lasta - f6);
          f1 = f1 != 2 or random(5) == 0;
          if (!f1) {
            f6 = -1;
          }
          if (f6 > -1) {
            trg.lasta = f6;
            xenf = f9[f6 * 2] * roxx;
            yenf = f9[f6 * 2 + 1] * roxx;
            f3 = Math.abs(xenf) > Math.abs(yenf);
            f1 = trg.xp + xenf * f7;
            f2 = trg.yp + yenf * f7;
            f1 = ingrid(f1, f2);
            if (levz[f1] < 1) {
              outgrid(f1);
              trg.xpp = xenf;
              trg.ypp = yenf;
            }
            if (f3) {
              trg.ybew = 0;
            } else {
              trg.xbew = 0;
            }
          }
          trg.fail = 0;
        }
      }

      function randrunx(f0) {
        newxx();
        if (trg.xpp != undefined) {
          trg.xpp = Math.min(620, Math.max(20, trg.xpp));
          trg.ypp = Math.min(447, Math.max(110, trg.ypp));
          xenf = trg.xp + trg.xbew - trg.xpp;
          yenf = trg.yp + trg.ybew - trg.ypp;
          enf = enfget(xenf, yenf);
          if (enf < 5) {
            trg.mode = 1;
            trg.xp = trg.xpp;
            trg.yp = trg.ypp;
            trg.xpp = undefined;
          } else {
            if (enfget(trg.xbew, trg.ybew) < 0.6) {
              if (trg.fail++ > 10) {
                trg.xpp = undefined;
              }
            }
          }
          enf = f0 / enf;
          xenf *= enf;
          yenf *= enf;
          trg.xbew -= xenf;
          trg.ybew -= yenf;
          if (trg.s == 97 or trg.s == 93) {
            trg.xbeww -= xenf * 3;
            trg.ybeww -= yenf * 3;
          }
          f1 = enfget(trg.xbew, trg.ybew);
          enf = roxx / f1;
          xenf = trg.xbew * enf;
          yenf = trg.ybew * enf;
          trg.nextl = ingrid(trg.xp + xenf, trg.yp + yenf);
          if (levz[trg.nextl] > 0.7 && f1 > 3) {
            if (trg.fail++ > 2) {
              trg.xpp = undefined;
            }
          }
          if (trg.xpp == undefined) {
            newxx();
            newxx();
          }
        }
      }

      function cirf(f1, f2, f3, f4) {
        var v1 = Math.random() * Math.PI;
        var v3 = (Math.PI / f4) * 2;
        z = 0;
        while (z < f4) {
          v1 += v3;
          f6 = Math.sin(v1) * f3;
          f7 = Math.cos(v1) * f3;
          ffmo(f1, f2, 0, f6, f7, 0, 9, trg.s, true);
          ++z;
        }
      }

      function quadf(f1, f2, f3, f4) {
        gibb += 10;
        if (f4 != 2) {
          ffmo(f1, f2, 0, f3, 0, 0, 9, trg.s, true);
          ffmo(f1, f2, 0, -f3, 0, 0, 9, trg.s, true);
          ffmo(f1, f2, 0, 0, f3, 0, 9, trg.s, true);
          ffmo(f1, f2, 0, 0, -f3, 0, 9, trg.s, true);
        }
        f3 /= Math.SQRT2;
        if (f4) {
          ffmo(f1, f2, 0, f3, f3, 0, 9, trg.s, true);
          ffmo(f1, f2, 0, -f3, f3, 0, 9, trg.s, true);
          ffmo(f1, f2, 0, f3, -f3, 0, 9, trg.s, true);
          ffmo(f1, f2, 0, -f3, -f3, 0, 9, trg.s, true);
        }
      }

      function ffmo(f1, f2, f3, f4, f5, f6, f7, f8) {
        var v1 = create(f1, f2, f3, f4, f5, f6, f7, trg.s);
        if (trg.spid > 0) {
          v1.xbew *= 0.5;
          v1.ybew *= 0.5;
        }
        if (trg.s == 68 && !altboss) {
          colorit(v1, 0.6, 1.2, 0.2, 50, 60, 0);
        }
        v1.ggh = false;
        if (!f8) {
          v1.dm = -3;
          v1.fd = 0.1;
        }
        if (trg.s == 26 && trg.alter == 3 or trg.s == 65 && altboss or trg.s == 102 && (trg.state > 0 or altboss && random(5) == 0) or trg.minb == 3 or trg.s == 98 && trg.specoz) {
          v1.hom = true;
          colorit(v1, 0.8, 1, 2.5, 0, 0, 0);
          v1._xscale *= 1.5;
          v1._yscale *= 1.5;
        } else {
          if (trg.s == 102) {
            var v2 = new flash.geom.Transform(v1);
            v2.colorTransform = bull;
          }
        }
        if (v3) {
          v1.dm -= 1;
          v1.xbew *= 1.2;
          v1.ybew *= 1.2;
          v1.xbew += trg.xbew * 0.4;
          v1.ybew += trg.ybew * 0.4;
        }
        if (trg.s == 79) {
          v1.dm += 3;
          v1.dy -= 15;
          v1.xbew *= 1.2;
          v1.ybew *= 1.2;
        } else {
          if (trg.s == 36) {
            v1.fd *= 0.4;
          } else {
            if (trg.s == 42) {
              v1.dm -= 3;
              v1.dy = -10;
              v1.ggh = true;
              v1.nog = 15;
            }
          }
        }
        if (trg.s == 59) {
          v1.dy += 15;
        }
        if (trg.champion or trg.s == 59 or trg.s == 57 or trg.s == 53 or trg.s == 43 or trg.s == 75 or trg.s == 76 or trg.s == 84) {
          v1.belial = true;
          v1.d._yscale = 140;
          v1.d._xscale = 140;
        }
        if (trg.s == 42 or trg.s == 38 or trg.s == 27) {
          v1.fd -= 0.05;
          v1.xbew *= 1.07;
          v1.ybew *= 1.07;
        }
        if (trg.s == 57) {
          v1.dy += 15;
          v1.dm -= 0.2;
        }
        if (trg.s == 90) {
          v1.dy -= 20;
          v1.dm += 2;
        }
        if (trg.s == 84) {
          v1.fd -= 0.07000000000000001;
        }
        if (trg.s == 65) {
          v1.dy -= 45;
          v1.dm += 7;
        }
        if (trg.s == 62) {
          v1.dy -= 50;
          v1.fd = 0.3;
          v1.xbew -= worm[1].xbew * 0.4;
          v1.ybew -= worm[1].ybew * 0.4;
        }
        if (trg.s == 100 or trg.s == 101 && altboss) {
          if (trg.specoz == 18) {
            colorit(v1, 0.2, 0.2, 0.2, 0, 0, 0);
            return v1;
          }
          colorit(v1, 0.3, 0.8, 0.8, 140, 140, 140);
        }
        return v1;
      }

      function shots(v1, v2, xenf, yenf, v3) {
        if (trg.s == 14 && trg.alter == 2 or trg.s == 86) {
          ffmo(v1, v2, 0, xenf * 0.8 - yenf * 0.2, yenf * 0.8 + xenf * 0.2, 0, 9);
          ffmo(v1, v2, 0, xenf * 0.8 + yenf * 0.2, yenf * 0.8 - xenf * 0.2, 0, 9);
        } else {
          if (v3 == 2) {
            if (v3) {
              ffmo(v1, v2, 0, xenf * 0.9 - yenf * 0.1, yenf * 0.9 + xenf * 0.1, 0, 9);
              ffmo(v1, v2, 0, xenf * 0.9 + yenf * 0.1, yenf * 0.9 - xenf * 0.1, 0, 9);
              ffmo(v1, v2, 0, xenf * 0.7 - yenf * 0.3, yenf * 0.7 + xenf * 0.3, 0, 9);
              ffmo(v1, v2, 0, xenf * 0.7 + yenf * 0.3, yenf * 0.7 - xenf * 0.3, 0, 9);
            }
          } else {
            trg2 = ffmo(v1, v2, 0, xenf, yenf, 0, 9);
            if (v3 or trg.s == 38 && trg.alter == 2) {
              ffmo(v1, v2, 0, xenf * 0.8 - yenf * 0.2, yenf * 0.8 + xenf * 0.2, 0, 9);
              ffmo(v1, v2, 0, xenf * 0.8 + yenf * 0.2, yenf * 0.8 - xenf * 0.2, 0, 9);
            }
            if (trg.s == 36 or trg.s == 56 or trg.s == 27 && trg.alter == 2 or trg.s == 84) {
              ffmo(v1, v2, 0, xenf * 0.6800000000000001 - yenf * 0.42, yenf * 0.58 + xenf * 0.42, 0, 9);
              ffmo(v1, v2, 0, xenf * 0.6800000000000001 + yenf * 0.42, yenf * 0.58 - xenf * 0.42, 0, 9);
              trg2.xbew *= 0.85;
              trg2.ybew *= 0.9;
            }
          }
        }
      }

      function firemode(siz, f1, f2) {
        if (trg.s == 56 or trg.s == 90) {
          siz += 60;
        } else {
          if (trg.s == 42 or trg.s == 38 or trg.s == 27) {
            siz += 40;
          }
        }
        if (trg.s == 56) {
          f1 += 5;
        }
        if (trg.s == 90) {
          f1 += 2 + random(2);
        }
        if ((fra + trg.e) % 7 == 0 or f2) {
          if (trg.fire <= 0) {
            enf = enfcheck(trg.xp, trg.yp, player.xp, player.yp, siz);
            if (enf) {
              if (linechecky(trg.xp, trg.yp, player.xp, player.yp)) {
                if (trg.s == 42) {
                  trg.d.gotoAndStop(2);
                } else {
                  if (trg.s == 86) {
                    sideflip(-xenf);
                  } else {
                    sideflip(xenf);
                  }
                  if (trg.s == 79) {
                    trg.d.gotoAndStop(8);
                  } else {
                    if (trg.s == 63) {
                      trg.d.gotoAndStop(9);
                    } else {
                      trg.d.gotoAndStop(5);
                    }
                  }
                }
                trg.fire = f1;
                trg.fir = -7;
                if (trg.s == 27) {
                  trg.fir = -25;
                  trg.fire += 6;
                }
              }
            }
          }
          if (!trg.free or slow <= 0 or fra % 2 == 0) {
            --trg.fire;
          }
        }
        if (trg.fir++ > 0 && (trg.s != 79 or trg.d.d._currentframe == 17) && (trg.s != 56 or trg.d.d._currentframe == 33) && (trg.s != 63 or trg.d.d._currentframe == 19)) {
          if (trg.s == 63 or trg.s == 79) {
            enf = enfcheck(trg.xp, trg.yp, player.xp + player.xbew * 5, player.yp + player.ybew * 5, 1000);
          } else {
            enf = enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
          }
          if (trg.s == 86) {
            sideflip(-xenf);
          } else {
            sideflip(xenf);
          }
          trg.fir = undefined;
          enf = enfget(xenf, yenf);
          enf = -7 / enf;
          xenf *= enf;
          yenf *= enf;
          if (trg.s == 63) {
            xenf *= 1.3;
            yenf *= 1.3;
          }
          if (trg.s == 42 && trg.alter == 2) {
            trg2 = green();
            trg2.dm -= 3;
            trg2.dy = -10;
            trg2.ggh = true;
            trg2.nog = 15;
          } else {
            if (trg.s == 63 && trg.specoz) {
              bossfire(10, true);
            } else {
              shots(trg.xp, trg.yp, xenf, yenf, trg.s == 27 or trg.s == 63 or trg.s == 90);
            }
          }
        }
      }

      function firewalk() {
        if (trg.fire <= 0) {
          f1 = trg.xp;
          f2 = trg.yp;
          enf = enfget(trg.xbew, trg.ybew);
          enf = -5 / enf;
          if (trg.s == 19) {
            enf *= 1.5;
          }
          trg.fire = 40 + random(20);
          var v1 = create(f1, f2, 0, -trg.xbew * enf, -trg.ybew * enf, 0, 9, trg.s);
          v1.fd = 0.3;
          v1.dm = -5;
          if (trg.s == 19 && altboss) {
            v1 = create(f1, f2, 0, (-trg.xbew - trg.ybew * 0.2) * enf, (trg.xbew * 0.2 - trg.ybew) * enf, 0, 9, trg.s);
            v1.fd = 0.3;
            v1.dm = -5;
            v1 = create(f1, f2, 0, (-trg.xbew + trg.ybew * 0.2) * enf, (-trg.xbew * 0.2 - trg.ybew) * enf, 0, 9, trg.s);
            v1.fd = 0.3;
            v1.dm = -5;
          }
        }
        --trg.fire;
      }

      function angstfind(v1, v2) {
        if (v1 == undefined) {
          v1 = player.xp;
          v2 = player.yp;
        }
        if (trg.failfind <= 0) {
          trg.failfind = 0;
        }
        trg.failfind = Math.min(trg.failfind, 20);
        topz(8);
        if ((trg.e + fra) % 14 == 1) {
          f13 = linecheckx(trg.xp, trg.yp, v1, v2);
          if (f13) {
            siz = 250;
            if (trris + 45 + random(100) <= fra && random(4) == 0 && trg.s < 90) {
              trris = fra;
              _root.soundy('Scared_Whimper_' + random(3) + '.mp', 100);
            }
          } else {
            siz = 170;
          }
          if (enfcheck(trg.xp, trg.yp, v1, v2, siz)) {
            if (trg.needmove <= 0) {
              trg.ypp = undefined;
              trg.xpp = trg.ypp;
            }
            trg.needmove = 3;
          } else {
            --trg.needmove;
          }
        }
        if ((trg.e + fra) % 30 == 0) {
          trg.checked = [];
        }
        if (trg.needmove > 0) {
          if (trg.rpx) {
            trg.rpx = undefined;
            trg.xpp = undefined;
          }
          f0 = enfcheck(trg.xp, trg.yp, v1, v2, 500);
          if (trg.xpp == undefined or trg.failfind > 20) {
            if (f0 > 0) {
              f1 = 1.5 / f0;
              trg.xbew += xenf * f1;
              trg.ybew += yenf * f1;
              enf = 30 / f0;
              var v4 = xenf * enf + trg.xp;
              var v5 = yenf * enf + trg.yp;
            } else {
              var v4 = trg.xp;
              var v5 = trg.yp;
            }
            i = 0;
            for (;;) {
              if (!(trg.xpp == undefined && i < 7 - trg.failfind * 0.3)) break;
              f10 = 450 * Math.random() + 30;
              if (random(2) == 0) {
                if (Math.abs(xenf) > Math.abs(yenf)) {
                  yenf = 0;
                } else {
                  xenf = 0;
                }
              }
              xenf = v4 + crand(f10);
              yenf = v5 + crand() * 0.5;
              f1 = ingrid(xenf, yenf);
              if (trg.checked[f1]) {
                i -= 0.7;
              } else {
                outgrid(f1);
                trg.checked[f1] = true;
                if (!mhit(xenf, yenf)) {
                  if (linecheckx(trg.xp, trg.yp, xenf, yenf)) {
                    f13 = !linecheckx(v1, v2, xenf, yenf);
                    if (f13 or trg.failfind >= 20) {
                      f7 = xenf;
                      f8 = yenf;
                      if (enfcheck(v1, v2, trg.xpp, trg.ypp, 100 + f0 + f10 / 3 + trg.failfind - trg.noco * 10)) {
                        ++trg.noco;
                      } else {
                        trg.xpp = f7;
                        trg.ypp = f8;
                        i = 100;
                        if (f13) {
                          trg.failfind /= 2;
                        }
                      }
                    } else {
                      trg.failfind += 0.35;
                    }
                  }
                }
              }
              ++i;
            }
          }
          if (trg.xpp != undefined) {
            if ((trg.e + fra) % 10 == 1) {
              f13 = enfcheck(v1, v2, trg.xpp, trg.ypp, 200);
              if (linecheckx(v1, v2, trg.xpp, trg.ypp) && trg.failfind < 20 or f13 or Math.abs(xenf) < 20 or Math.abs(yenf) < 20) {
                trg.ypp = undefined;
                trg.xpp = trg.ypp;
              }
            }
            pathfind(trg, trg.xpp, trg.ypp, 1.3);
          }
        } else {
          trg.failfind *= 0.9;
          trg.rpx = true;
          trg.noco = 0;
          randrun();
          trg.xbew *= 0.9;
          trg.ybew *= 0.9;
        }
        tip(8);
      }

      function pffy(f1, f2) {
        if (trg.s != 54) {
          f1 = ingrid(f1, f2);
          if (levz[f1] == 0.99) {
            f44 = webs[f1] && trg == player;
          }
          f3 = levz[f1] == 0.99 && (!f44 && !webs[f1]) && (!trg.flyby or _root.lev == _root.sacrificeRoom or _root.lev == _root.curseRoom) && !trg.flyai;
          if (f3) {
            f55 = f1;
          }
          if (levz[f1] > 1 && levz[f1] < 2 or f3) {
            var v4 = this['de' + f1];
            if (v4.fire && trg.s != 28 or f3) {
              relf = f3;
              if (trg.s == 27) {
                trg.dones = true;
              }
              outgrid(f1);
              enf = enfcheck(trg.xp, trg.yp, xenf, yenf, siz);
              if (f3) {
                enf += 20;
              }
              if (trg.s == 29 && trg.alter != 2 && v4.fire) {
                trg.s = 54;
                attach(trg, 54);
                trg.hp += 20;
              }
              if (enf < siz) {
                if (!f3 && trg.firs + 10 <= fra) {
                  trg.firs = fra;
                  _root.soundy('Firedeath_hiss.wav', Math.min(100, 50 + trg.hp * 5));
                }
                siz = enf;
                f4 = xenf;
                f5 = yenf;
                f6 = enf;
                f7 = f3;
                return true;
              }
            }
          }
        }
      }

      function firecheck(trg) {
        trg3 = 0;
        siz = 38;
        var v3 = 20;
        relf = true;
        var v4 = pffy(trg.xp + v3, trg.yp + v3) or pffy(trg.xp - v3, trg.yp + v3) or pffy(trg.xp + v3, trg.yp - v3) or pffy(trg.xp - v3, trg.yp - v3);
        if (v4) {
          if (!f7) {
            xenf = f4;
            yenf = f5;
            enf = f6;
            enf = 4 / enf;
            trg.xbew += xenf * enf;
            trg.ybew += yenf * enf;
          }
        }
        if (dang) {
          if (trg == player && (!trg.flyby or _root.lev == _root.sacrificeRoom or _root.lev == _root.curseRoom)) {
            if (shit(trg.xp, trg.yp)) {
              if (blackout == 2 or spidboss) {
                if (trg == player) {
                  playslow = 10;
                }
              } else {
                v4 = true;
                relf = 2;
              }
            }
          }
        }
        if (dang2 && !trg.flyby && !trg.flyai) {
          if (trg != player) {
            if (dang2.hitTest(trg.xp, trg.yp, true)) {
              v4 = true;
            }
          }
        }
        return v4;
      }

      function breakfloor(f1) {
        if (levz[f1] < 0.99) {
          var v1 = true;
          for (i in brr) {
            v1 = v1 && f1 != brr[i];
          }
          for (i in brr2) {
            v1 = v1 && f1 != brr2[i];
          }
          if (v1) {
            v1 = [levz[f1 + 1] == 3, levz[f1 + rowz] == 3, levz[f1 - 1] == 3, levz[f1 - rowz] == 3];
            if (v1[0] && v1[2] or v1[1] && v1[3]) {
              brr.push(f1);
            } else {
              brr2.push(f1);
            }
          }
        }
      }

      function breakall() {
        f1 = false;
        for (i in brr) {
          f1 = brr[i];
          outgrid(f1);
          tiles.gotoAndStop(67);
          maxx = new flash.geom.Matrix();
          maxx.translate(xenf, yenf);
          maxx.scale(hdx, hdx);
          dblock.draw(tiles, maxx);
        }
      }

      function pathcheck(trg, v2, v3) {
        v1 = ingrid(trg.xp, trg.yp);
        trg.gridder = levz.slice(0, -1);
        z = 0;
        for (z in v3) {
          trg.gridder[v3[z]] = 1;
        }
        trg.gridder[v2] = 0;
        acts = [];
        acts2 = [];
        z = -1;
        for (;;) {
          if (!(z > -100 && trg.gridder[v2] >= 0)) break;
          if (z == -1) {
            pff(v1, -1);
          } else {
            for (i in acts) {
              v1 = trg.gridder[acts[i]];
              if (v1 < z) {
                acts2.push(acts[i]);
              } else {
                outgrid(acts[i]);
                pff(ingrid(xenf, yenf + roxx), v1);
                pff(ingrid(xenf + roxx, yenf), v1);
                pff(ingrid(xenf - roxx, yenf), v1);
                pff(ingrid(xenf, yenf - roxx), v1);
              }
            }
          }
          acts2[acts2.length] = 0;
          acts = acts2.slice(0, -1);
          acts2 = [];
          --z;
        }
        if (z < -99) {
          trg.gridder = 0;
          return false;
        } else {
          return z;
        }
      }

      function bloww(v2) {
        _root.levblow[_root.lev].push(v2, f5, f6);
        dblock.fillRect(new flash.geom.Rectangle((xenf - roxx2 - 2) * hdx, (yenf - roxx2 - 2) * hdx, (roxx + 4) * hdx, (roxx + 4) * hdx), 0);
        if (levz[v2] == 0.99 && webs[v2]) {
          tiles.gotoAndStop(161 + webs[v2]);
          maxx = new flash.geom.Matrix();
          maxx.translate(xenf, yenf);
          maxx.scale(hdx, hdx);
          dblock.draw(tiles, maxx);
          webs[v2] = false;
          levz[v2] = 0;
        } else {
          if (levz[v2] == 1) {
            gibs(xenf, yenf);
            ++_root.so.data.rocksBombed;
            if (_root.so.data.rocksBombed > 49) {
              _root.SecretUnlocked[18] = true;
            }
            if (_root.floorNum < 7 or _root.floorNum == 9) {
              _root.soundy('Rock_crumble ' + random(3) + '.wav', 100);
              tiles.gotoAndStop(60 + random(5));
            } else {
              _root.soundy('Meaty_Deaths_' + random(6) + '.mp', 100);
              tiles.gotoAndStop(85 + random(5));
            }
            maxx = new flash.geom.Matrix();
            maxx.translate(xenf, yenf);
            maxx.scale(hdx, hdx);
            dblock.draw(tiles, maxx);
            if (Math.abs(f5) > Math.abs(f6)) {
              f6 = 0;
              if (f5 > 0) {
                f5 = roxx;
              } else {
                f5 = -roxx;
              }
            } else {
              f5 = 0;
              if (f6 > 0) {
                f6 = roxx;
              } else {
                f6 = -roxx;
              }
            }
            f1 = ingrid(xenf + f5, yenf + f6);
            if (levz[f1] == 3) {
              _root.levblow[_root.lev].push(f1);
              levz[f1] = 0;
              outgrid(f1);
              tiles.gotoAndStop(66);
              maxx = new flash.geom.Matrix();
              maxx.translate(xenf, yenf);
              maxx.scale(hdx, hdx);
              dblock.draw(tiles, maxx);
            }
            if (_root.rarer[_root.lev] == v2) {
              levz[v2] = 0;
              outgrid(v2);
              chestox = xenf;
              chestoy = yenf;
              chestopen = 2;
              _root.rarer[_root.lev] = -100;
              if (_root.so.data.rox++ > 30) {
                _root.SecretUnlocked[87] = true;
              }
            }
          }
        }
        levz[v2] = 0;
      }

      function gosplash() {
        if (trg.s == 4 or trg.s == 45 or trg.s == 101 or trg.s == 84 && !trg.dones) {
          if (!trg.dsound && trg.s != 101) {
            trg.dsound = true;
            _root.soundy('boss1_explosions' + random(3) + '.wav', 100);
          }
          if (trg.pois) {
            trg2 = parc('bloo', trg.xp, trg.yp);
            trg2._xscale *= 3;
            trg2._yscale = trg2._xscale;
            splater(trg.xp, trg.yp, trg.spl + 1 + random(10), Math.random() + 0.8);
            if (trg.pois == 4) {
            } else {
              if (blackout != 2) {
                colorit(trg2, 0, 2, 0, 0, 40, 0);
              } else {
                colorit(trg2, 0, 0, 0, 0, 0, 0);
              }
            }
          } else {
            _root.bomf[_root.lev].push([trg.xp, trg.yp]);
          }
          f4 = 60;
          if (trg.dmg > 25 && trg.s != 45 && trg.s != 101) {
            f4 = 90;
          }
          if (trg.dmg >= 45 && trg.s != 45 && trg.s != 101) {
            f4 = 105;
          }
          if (trg.s == 101 or trg.s == 45) {
            f4 = 44;
          }
          f11 = [];
          z = 0;
          while (z < 150) {
            var v2 = Math.random() * f4;
            f5 = crand(v2);
            f6 = crand();
            f1 = trg.xp + f5;
            f2 = trg.yp + f6;
            v2 = ingrid(f1, f2);
            if (levz[v2] >= 1.9 && f4 < 90 && _root.lev != _root.bossRoom && _root.lev != _root.bossRoom2) {
              f4 = 90;
            }
            outgrid(v2);
            if (!f11[v2]) {
              f11[v2] = true;
              if (levz[v2] > 0.9) {
                if (linecheckxx(trg.xp, trg.yp, xenf, yenf)) {
                  if (levz[v2] == 1 or levz[v2] == 1.85 or webs[v2]) {
                    bloww(v2, f5, f6);
                  } else {
                    killshit(v2, 10);
                  }
                  if (v2 < 40) {
                    breakfloor(v2);
                  }
                }
              }
            }
            ++z;
          }
          for (z in ball) {
            trg2 = ball[z];
            siz = 85 + sizes[Math.round(trg2.s)];
            if (trg.s == 45 && trg2 == player) {
              siz = 40;
            }
            enf = enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, siz);
            if (enf < siz && !trg2.dones && (trg.s == 4 or trg.s == 45 or trg.s == 101 && trg2 != player or trg2.s == 7) && trg2.bh && !trg2.shot) {
              f1 = false;
              if (trg2.s == 5 && trg2.d._currentframe == 8 && chestopen == undefined) {
                if (trg2.col == 41) {
                  trg2.d.d.gotoAndStop(30);
                } else {
                  if (trg2.col == 1) {
                    trg2.d.d.gotoAndStop(34);
                  } else {
                    if (trg2.col > 1) {
                      trg2.d.d.gotoAndStop(39);
                      trg2.dones = true;
                      _root.beggarKilled = true;
                    } else {
                      trg2.d.d.gotoAndStop(30);
                    }
                  }
                }
                trg2.spin = false;
                trg2.busted = true;
                chestopen = trg2;
                f1 = true;
              }
              if (trg2.s != 5 or fra - trg2.fra > 30 or f1) {
                enf = Math.min(siz - enf, 15) / enf;
                f1 = trg2.s == 7 or trg2.s == 8 or trg2.s == 45 or trg2.s == 101;
                f2 = true;
                if (!f1) {
                  f2 = linecheckxx(trg.xp, trg.yp, trg2.xp, trg2.yp);
                }
                if (f2) {
                  if (enf > 0) {
                    if (f1 or trg2.s > 61) {
                      enf *= 0.015;
                    }
                    if (trg2.s == 59) {
                      enf = 0;
                    }
                    trg2.xbew *= 0.5;
                    trg2.ybew *= 0.5;
                    trg2.xbew -= xenf * enf;
                    trg2.ybew -= yenf * enf;
                  }
                  if ((trg2.s == 46 or trg2.s == 68 or trg2.s == 87 or trg2.s == 67 or trg2.s == 30 or trg2.s == 88 or trg2.s == 59 or trg2.s == 64 or trg2.s == 78 or trg2.s == 82 or trg2.s == 83 or trg2.s == 101) && trg.dfr && !trg.ipecacBomb or trg2.s == 45 && trg.s == 45 or trg2.s == 52 && (trg.col == 3 or trg.col == 5)) {
                  } else {
                    if (trg2.s == 48) {	//Wrath
                      if (trg.wrathBomb) {
                        hurt(trg2, 10);
                      } else {
                        hurt(trg2, 100);
                      }
                    } else {
                      if (trg2.s == 28) {	//Chub/C.H.A.D./Carrion Queen
                        hurt(trg2, 18);
                      } else {
                        if (trg.dmg > 0) {
                          hurt(trg2, 50 + trg.dmg);
                        } else {
                          hurt(trg2, 40);
                        }
                      }
                      if (trg.poisonBombPower) {
                        trg2.poisonDuration = trg.poisonBombPower;
                        trg2.poisonDamage = 7;
                      }
                    }
                  }
                  if (trg2 == player && !trg.friend) {
                    if (trg.mug) {
                      playerhurt(0.5, 4);
                    } else {
                      playerhurt(1, 4);
                    }
                  }
                }
              }
            }
            trg2 = undefined;
          }
          if (trg.s != 45 && trg.s != 84 && trg.s != 101) {
            if (blackout == 2) {
              z = 0;
              while (z < 5) {
                splater(trg.xp + crand(), trg.yp + crand(random(10)), 1 + random(10), Math.random() + 1);
                ++z;
              }
            } else {
              if (!trg.pois) {
                maxx = new flash.geom.Matrix();
                if (f4 > 100) {
                  maxx.scale(1.5, 1.5);
                }
                maxx.translate(trg.xp, trg.yp);
                maxx.scale(hdx, hdx);
                splat.draw(crater, maxx);
              }
              if (trg.poisonBombPower) {
                gibs();
                z = 0;
                while (z < 20) {
                  f1 = z * 3;
                  splater(trg.xp + crand(f1), trg.yp + crand(f1), 31 + random(10), Math.random() * 0.5 + 1.2 - z / 20);
                  ++z;
                }
              }
            }
          }
        }
        big = 0;
        if (trg.s != 13 && trg.s != 14 && trg.s != 5 && trg.s != 18 && trg.s != 45 && trg.s != 80 && trg.s != 4.5 && trg.s != 85 && trg.s != 101 && !trg.fart) {
          gibs();
        }
        if (trg.frezz > 0) {
          _root.soundy('Rock_crumble ' + random(3) + '.wav', 100);
        } else {
          if (trg.s == 38 or trg.s == 59 or trg.s == 77) {
            _root.soundy('goodeath' + random(3) + '.wav', 180);
          } else {
            switch (big) {
              case 0:
                if (!trg.flyai && trg.s != 85) {
                } else {
                case 1:
                  _root.soundy('Death_Burst_Small_' + random(3) + '.mp', 100);
                  break;
                case 2:
                case 3:
                  if (trg.lasts or !trg.aboss) {
                    _root.soundy('Death_Burst_Large_' + random(2) + '.mp', 80 + random(40));
                  } else {
                    _root.soundy('Rocket_Blast_Death_1.wav');
                  }
                }
            }
          }
        }
      }

      function flya() {
        f1 = [13, 13, 13, 13, 13, 13, 13, 14, 18, 18, 18];
        i = 0;
        while (i < 4 / (1 + ashut * 0.2)) {
          f0 = Math.random() * 6;
          create(trg.xp + crand(f0), trg.yp + crand(f0), 0, 0, 0, 0, f1[random(f1.length)]);
          if (trg.s == 67) {
            i -= 0.5;
          }
          ++i;
        }
        f1 = 8;
      }

      function gibs(v1, v2) {
        big = 1;
        f10 = 0;
        f1 = 10;
        if (trg.s == 25 && !trg.nobomb or trg.s == 55 && trg.alter != 1) {
          bomf.push([trg.xp, trg.yp]);
        }
        if (trg.s == 4 or trg.s == 45 or trg.s == 84) {
          f2 = 7;
          f1 = -1;
        } else {
          f2 = 8;
        }
        if (v1 > 0 && v2 > 0) {
          f1 = 5;
        }
        if (v1 <= 0 or v2 <= 0) {
          v1 = trg.xp;
          v2 = trg.yp;
        }
        f1 /= 1 + gibb * 0.1;
        i = 0;
        while (i < f1) {
          ++gibb;
          f10 = Math.random() * 4;
          f11 = trg.s == 100 or trg.s == 97 or trg.s == 98 or trg.s == 99 or trg.s == 20 or trg.s == 43 or trg.s == 36 or trg.s == 28 or trg.s == 49 or trg.s >= 62 && !trg.sic && trg.s != 73 && trg.s != 71 && trg.s != 77 && trg.s != 74 && trg.s < 85 or trg.s == 57 or trg.champion or trg.minb;
          if (f11) {
            f10 *= 1.7;
            big = 2;
          }
          if (trg.s == 36 or trg.s == 19 or trg.s == 71 or trg.s == 74 or trg.s > 100) {
            big = 3;
            f10 *= 1.3;
          }
          var v1 = create(v1, v2, 0, crand(f10), crand(f10) * 0.5, 0, f2);
          if (f11 or trg.s == 19) {
            v1.ybew *= 1.4;
            v1.d._yscale = 100 + random(70);
            v1.d._xscale = v1.d._yscale;
          } else {
            if (trg.s == 36 or trg.s == 71 or trg.s == 74) {
              v1.d._yscale = 140 + random(80);
              v1.d._xscale = v1.d._yscale;
            }
          }
          if (trg.frezz > 0) {
            colorit(v1, 0.18, 0.22, 0.22, 60, 60, 60);
          } else {
            if (trg.poisonDuration > 0 or trg.spl == 30) {
              colorit(v1, 0.2, 1, 0.2, 0, 70, 17);
              v1.spl = 30;
            } else {
              if (trg.specol) {
                f1 = trg.specol;
                colorit(v1, specol[f1][0], specol[f1][1], specol[f1][2], 0, 0, 0);
              }
            }
          }
          ++i;
        }
      }

      function bombfail(f1, f2, f3, f4) {
        var v1 = create(f1, f2, 0, 0, 0, 0, 4);
        v1.pois = f4;
        v1.dones = true;
        if (f3 == 5) {
          trg.mager = true;
          return v1;
        }
        if (f3 == 4) {
          v1.dmg = 30;
          v1._yscale = 113;
          v1._xscale = 113;
          v1.d.gotoAndStop(2);
          return v1;
        }
        if (f3) {
          v1.dfr = true;
          if (f4 == 4) {
            v1.d.gotoAndStop(6);
          } else {
            v1.d.gotoAndStop(5);
          }
          if (blackout == 2) {
            colorit(v1, 0, 0, 0, 0, 0, 0);
          }
          return v1;
        }
        v1.d.gotoAndStop(2);
        return v1;
      }

      function bomb(f1) {
        if (fra - lastbo >= 30 or f1) {
          if (f1) {
            if (f1 != 2) {
            }
          } else {
            if (_root.bombs > 0) {
              --_root.bombs;
            } else {
              return false;
            }
          }
          lastbo = fra;
          _root.soundy('Fetus_Land_' + random(2) + '.wav', 100);
          trg2 = create(trg.xp, trg.yp, 0, 0, 0, 0, 4);
          trg2.dmg = 10;
          if (f1 == 4) {
            trg2.d.gotoAndStop(7);
            trg2.decoy = true;
          }
          if (f1 && f1 != 2 or haveEffect[106]) {
            trg2.dmg += 50;
            trg2._yscale = 123;
            trg2._xscale = 123;
            trg2.col = 4;
            if (haveEffect[140]) {
            }
          }
          if (haveEffect[140]) {
            trg2.poisonBombPower = 130;
            trg2.col = 6;
          }
          ++_root.so.data.bomb;
          return trg2;
        }
      }

      function killshit(v2, v3) {
        if (levz[v2] > 1 && levz[v2] < 1.8) {
          trg2 = this['de' + v2];
          if (!trg2.gold or random(3) == 0) {
            levz[v2] -= 0.13;
            if (trg2._currentframe == 6) {
              trg2.gotoAndStop(2);
            } else {
              trg2.nextFrame();
            }
            if (v3 && levz[v2] > 1 && !trg2.gold) {
              levz[v2] -= 0.13;
              trg2.nextFrame();
            }
            if ((random(3) == 0 or v3 > 5) && !trg2.gold) {
              levz[v2] -= 0.13;
              trg2.nextFrame();
            }
            if (trg2.nam == 'breakblock' && random(3) == 0 or v3 > 7) {
              levz[v2] -= 0.13;
              trg2.nextFrame();
            }
            if (trg2._currentframe == 6 && levz[v2] < 1.1) {
              trg2.gotoAndStop(5);
            }
            if (levz[v2] <= 1) {
              trg2.dones = true;
              switch (trg2.nam) {
                case 'locktile':
                  trg2.gotoAndStop(2);
                  break;
                case 'breakblock':
                case 'breakblock2':
                case 'breakblock3':
                  if (!trg2.cent) {
                    ++_root.so.data.poopsDestroyed;
                    if (_root.so.data.poopsDestroyed > 50) {
                      _root.SecretUnlocked[46] = true;
                    }
                  }
                  _root.soundy('plop.wav', 100);
                  trg2.gotoAndStop(5);
                  break;
                case 'fireblock':
                case 'fireblock2':
                  _root.soundy('steam_halfsec.wav', 85);
                  trg2.gotoAndStop(5);
              }
              if (trg2.xp == undefined) {
                trg2.xp = trg2._x;
                trg2.yp = trg2._y;
              }
              if (trg2.gold) {
                chestopen = trg2;
              } else {
                if (trg2.nam == 'breakblock2') {
                  trg2.fra = fra + 120;
                  shiz.push(trg2);
                } else {
                  if (Math.random() < 0.1 && (!trg2.cent or random(5) == 0) && !trg2.egg && !v3) {
                    if (Math.random() < 0.25 or trg2.cent) {
                      f0 = 5;
                    } else {
                      f0 = 5.02;
                    }
                    create(trg2.xp, trg2.yp, 0, 0, 0, 0, f0);
                  }
                }
              }
              levz[v2] = 0.9;
              clevc[v2] = 0;
              if (trg2.egg) {
                bomf.push([trg2.xp, trg2.yp]);
              }
            }
            _root.levsav[_root.lev][trg2.savv] = trg2._currentframe;
            return true;
          }
        } else {
          return false;
        }
      }

      function moveon() {
        if (_root.floorNum == 11 && _root.lev == _root.bossRoom) {
        }
        _root.aloc();
        _root.lastl = _root.lev;
        _root.mapa._visible = false;
        _root.hud._visible = false;
        onEnterFrame = undefined;
      }

      function getf() {
        if (Math.abs(xenf) > Math.abs(yenf)) {
          if (xenf > 0) {
            f1 = 2;
          } else {
            f1 = 1;
          }
        } else {
          if (yenf < 0) {
            f1 = 4;
          } else {
            f1 = 3;
          }
        }
        if (altboss && trg.s == 19) {
          f1 += 4;
        }
      }

      function bosssp() {
        if (!trg.firsttx && !nobob) {
          nobob = true;
          trg.firsttx = true;
          if (_root.floorNum == 6 && _root.lev != _root.bossRoom2) {
            checkTreasureSkip();
            if (_root.treasuresSkipped > 1) {
              _root.SecretUnlocked[88] = true;
            }
          }
          if ((_root.floorNum < 8 or _root.floorNum == 8 && _root.labyrinthCurse && _root.lev == _root.bossRoom2) && (_root.floorNum != 6 or _root.SecretUnlocked[4] && (_root.challenge > 4 or _root.challenge == 0))) {
            if (_root.lev != _root.bossRoom2) {
              create(320, 200, 0, 0, 0, 0, 5.09);
            }
            create(320, 360, 0, 0, 0, 0, 5.1);
            f1 = ingrid(320, 200);
            bloww(f1);
            f1 = ingrid(320, 360);
            bloww(f1);
          } else {
            if (_root.floorNum == 9 or _root.challenge < 9) {
              f1 = _root.lox[_root.challenge];
              if (f1 > 0) {
                _root.SecretUnlocked[f1] = true;
              }
            }
            if (_root.floorNum == 6) {
            } else {
              if (_root.floorNum == 11) {
                f10 = [91, 92, 96, 93, 97, 94, 95];
                _root.SecretUnlocked[f10[_root.characterID]] = true;
                _root.SecretUnlocked[75] = true;
              } else {
                if (_root.floorNum == 9) {
                  if (_root.altchap) {
                    f10 = [65, 66, 67, 68, 70, 69, 72];
                    _root.SecretUnlocked[f10[_root.characterID]] = true;
                    if (_root.so.data.polaroidCounter++ >= 5) {
                      _root.SecretUnlocked[74] = true;
                    }
                    if (haveTrinket(47)) {
                    }
                  } else {
                    f10 = [55, 59, 60, 63, 62, 61, 73];
                    _root.SecretUnlocked[f10[_root.characterID]] = true;
                  }
                } else {
                  if (_root.lev != _root.bossRoom2) {
                    _root.SecretUnlocked[3] = true;
                    if (_root.characterID == 5) {
                      _root.SecretUnlocked[58] = true;
                    } else {
                      if (_root.characterID == 4) {
                        _root.SecretUnlocked[38] = true;
                      } else {
                        if (_root.characterID == 6) {
                          _root.SecretUnlocked[71] = true;
                        } else {
                          if (_root.characterID >= 1) {
                            _root.SecretUnlocked[25 + _root.characterID] = true;
                          }
                        }
                      }
                    }
                  }
                }
              }
              if (_root.lev != _root.bossRoom2) {
                ++_root.so.data.momKills;
                if (_root.so.data.momKills > 10 && _root.floorNum < 9) {
                  if (_root.challenge == 9) {
                    create(320, 280, 0, 0, 0, 0, 5.09);
                  } else {
                    if (_root.challenge == 10) {
                      create(320, 280, 0, 0, 0, 0, 5.34);
                    } else {
                      create(280, 280, 0, 0, 0, 0, 5.09);
                      create(360, 280, 0, 0, 0, 0, 5.34);
                    }
                  }
                } else {
                  create(320, 280, 0, 0, 0, 0, 5.34);
                }
                if (_root.so.data.momKills > 15) {
                  _root.SecretUnlocked[89] = true;
                }
              }
            }
          }
          if (_root.lev == _root.bossRoom) {
            if (_root.floorNum == 2 or _root.floorNum == 4 or _root.floorNum == 6 or _root.floorNum == 8) {
              if (_root.nodmg) {
                _root.SecretUnlocked[48 + _root.floorNum / 2] = true;
              }
              _root.nodmg = true;
              if (_root.floorNum == 6 && _root.SecretUnlocked[74]) {
                dropPolaroid = true;
                create(200, 300, 0, 0, 0, 0, 5.35);
              }
            }
          }
          ++_root.levelsCompleted[_root.floorNum];
          _root.bossKilled[_root.bossID] = true;
          if (_root.bossID >= 9 && _root.bossID <= 12 or _root.bossID == 22) {
            ++_root.horsedown;
          }
          if (_root.bossKilled[1] && _root.bossKilled[2] && _root.bossKilled[13] && _root.bossKilled[17]) {
            _root.SecretUnlocked[19] = true;
          }
          if (_root.bossKilled[3] && _root.bossKilled[4] && _root.bossKilled[14] && _root.bossKilled[18]) {
            _root.SecretUnlocked[20] = true;
          }
          if (_root.bossKilled[5] && _root.bossKilled[6] && _root.bossKilled[15]) {
            _root.SecretUnlocked[21] = true;
          }
          if (_root.bossKilled[9] && _root.bossKilled[10] && _root.bossKilled[11] && _root.bossKilled[12] && _root.horsedown >= 4) {
            _root.SecretUnlocked[25] = true;
          }
          if (_root.floorNum == 2) {
            _root.SecretUnlocked[13] = true;
          }
          if (_root.floorNum == 4) {
            _root.SecretUnlocked[14] = true;
          }
          if (_root.levelsCompleted[2] >= 25) {
            _root.SecretUnlocked[22] = true;
          }
          if (_root.levelsCompleted[4] >= 20) {
            _root.SecretUnlocked[23] = true;
          }
          if (_root.levelsCompleted[6] >= 15) {
            _root.SecretUnlocked[24] = true;
          }
        }
      }

      function firr(trg) {
        var v3 = haveEffect[6] * 1.5 + (haveEffect[32] + haveEffect[80] + haveEffect[1] + haveEffect[120]) * 0.7 + (haveEffect[196] + haveEffect[59] - haveEffect[182]) * 0.4 + (haveEffect[101] + haveEffect[90] + haveEffect[189]) * 0.2;
        if (haveEffect[120]) {
          ++v3;
        }
        if (_root.characterID == 6) {
          v3 -= 0.25;
        }
        f1 = Math.sqrt(Math.max(0, 1 + v3 * 1.3));
        trg.fire = Math.max(5, 16 - f1 * 6 - Math.min(v3, 0) * 6);
        if (haveEffect[69]) {
          trg.fire *= 0.8;
        }
        if (haveEffect[2]) {
          trg.fire *= 2.1;
          trg.fire += 3;
        }
        if (haveTrinket(39)) {
          trg.fire -= 2;
        }
        if (trg == player) {
          _root.fireRate = trg.fire;
        }
      }

      function bossfire(f10, f9, f11, f12, f13) {
        f1 = trg.xp;
        f2 = trg.yp;
        f3 = 10;
        if (f11 <= 0) {
          f11 = 0;
        }
        if (helpss > 1 && trg.s == 20) {
          f10 *= 0.6;
        }
        if (helpss > 2 && trg.s == 20) {
          f10 *= 0.8;
        }
        i = 0;
        while (i < f10) {
          if (f9) {
            yenf = 0;
            xenf = 0;
            if (f12 != 0 or f12 == undefined) {
              xenf = trg.xp - player.xp;
            }
            if (f13 != 0 or f13 == undefined) {
              yenf = trg.yp - player.yp;
            }
            if (f13) {
              if (f13 * yenf > 0) {
                yenf = 0;
              }
              yenf *= Math.abs(f13);
            }
            if (f12) {
              if (f12 * xenf > 0) {
                xenf = 0;
              }
              xenf *= Math.abs(f12);
            }
            enf = enfget(xenf, yenf);
            enf = -7 / enf;
            xenf *= enf;
            yenf *= enf;
            f14 = Math.random() * 3.5;
            if (trg.worm && f10 == 1) {
              f14 *= 3;
            }
            xenf += crand(f14);
            yenf += crand();
          } else {
            xenf = crand(7);
            yenf = crand();
          }
          f0 = Math.random() * 6;
          trg2 = create(trg.xp, trg.yp, 0, xenf, yenf, 0, 9, trg.s);
          trg2.fd = 0.32 + f11 * 0.1;
          trg2.dm = -random(30) * 0.8 + 5 - f11;
          trg2.d._yscale = 90 + random(2) * 40 + Math.random() * 5;
          trg2.d._xscale = trg2.d._yscale;
          if (trg.s == 62) {
            trg2.dy -= 50;
          }
          if (trg.s == 102 or trg.minb == 3) {
            if (random(10) == 0 && altboss or trg.minb == 3) {
              trg2.hom = true;
              colorit(trg2, 0.8, 1, 2.5, 0, 0, 0);
              trg2._xscale *= 1.2;
              trg2._yscale *= 1.2;
              if (trg.minb == 3) {
                trg.fd -= 1;
              }
            } else {
              var v3 = new flash.geom.Transform(trg2);
              v3.colorTransform = bull;
            }
          }
          ++i;
        }
        return trg2;
      }

      function newstart(f1, f22) {
        if (f1) {
          _root.hp = 100;
          newstats();
          _root.newstartt = true;
        } else {
          _root.getup = true;
          if (_root.floorNum != 11) {
            ++_root.floorNum;
          }
          if (!f22) {
            _root.cuts = true;
          }
        }
        _root.levz = undefined;
        _root.door = -1;
        _root.playery = 0;
        _root.playerx = 0;
        moveon();
        _root.gotoAndStop('reset');
      }

      function plff() {
        plox = Math.max(7, plox);
        if (haveEffect[69] or haveEffect[118] && (xenf != 0 or yenf != 0)) {
          chax = xenf;
          chay = yenf;
          if (chaf == undefined) {
            chaf = fra + Math.max(0, _root.fireRate - 10) * 4;
            lchaf = chaf;
          }
        }
        if (xenf != 0 or yenf != 0) {
          xxenf = xenf;
          yyenf = yenf;
        }
        if (haveEffect[152] && fra % 3 == 0) {
          trg.xpp = xenf;
          trg.ypp = yenf;
          lasershow(trg, 5);
          trg.lass = lass;
          trg.lfrr = fra;
          llss = true;
          xenf = trg.xpp;
          yenf = trg.ypp;
          secol *= 0.8;
          secol += 0.2;
        }
        if (haveEffect[152] && (sob == -1 or _root.hat[11]) && trg.fire < 0) {
          secol += 1;
          firr(trg);
          sob = 1;
        }
        if (trg.fire < 0 && (!haveEffect[69] && !haveEffect[118] or chaz or _root.bombnext) && unic <= 0 && (xenf != 0 or yenf != 0)) {
          firr(trg);
          if (haveEffect[118] && !_root.bombnext) {
            trg.fire = 20;
            f11 = true;
            trg.xpp = xenf;
            trg.ypp = yenf;
            trg.xbew *= 0.7;
            trg.ybew *= 0.7;
          } else {
            f11 = haveEffect[68] && !_root.bombnext && !haveEffect[52];
            if (f11) {
              trg.xpp = xenf;
              trg.ypp = yenf;
              trg.d.d.d.d.d.gotoAndStop(plo);
              lasershow(trg, true);
              _root.soundy('RedLightning_Zap_' + random(3) + '.mp', 60);
              llss = true;
              xenf = trg.xpp;
              yenf = trg.ypp;
            } else {
              llss = false;
            }
          }
          enf = enfget(xenf, yenf);
          enf = 10 / enf;
          xenf *= enf;
          yenf *= enf;
          xxenf = xenf;
          yyenf = yenf;
          xenf += trg.xbew * 0.6;
          yenf += trg.ybew * 0.6;
          enf = enfget(xenf, yenf);
          if (enf < 10) {
            enf = 10 / enf;
            xenf *= enf;
            yenf *= enf;
          }
          if (sob == 1 && !_root.hat[11]) {
            sob = -1;
          } else {
            sob = 1;
          }
          v1 = 0.3 + Math.random() * 0.2;
          if (haveEffect[2]) {
            v1 = 0.8;
            sob = 1;
          }
          f1 = trg.xp - yenf * sob * v1;
          f2 = trg.yp + xenf * sob * v1;
          if (!llss) {
            _root.soundy('Tears_Fire_' + random(3) + '.mp');
          }
          if (haveEffect[55] && (random(2) == 0 or haveEffect[2]) or haveEffect[87] && random(8) == 0) {
            f1 = trg.xp;
            f2 = trg.yp;
            create(f1, f2, 0, -xxenf, -yyenf, 0, 2);
            if (haveEffect[87]) {
              create(f1, f2, 0, -yyenf, xxenf, 0, 2);
              create(f1, f2, 0, yyenf, -xxenf, 0, 2);
            }
          }
          if (haveEffect[168] && !_root.bombnext) {
            trg.fire = -1;
            if (missileTimer <= 0) {
              missileTimer = 30;
              drop = create(player.xp, player.yp, 0, 0, 0, 0, 37);
              drop.d.gotoAndStop(70);
            }
          } else {
            if (!f11) {
              var v2 = create(f1, f2, 0, xenf, yenf, 0, 2);
              if (haveEffect[52] && !_root.bombnext) {
                trg.fire *= 3;
                trg.fire += 10;
                enf = 14 / enfget(v2.xbew, v2.ybew);
                v2.xbew *= enf;
                v2.ybew *= enf;
                v2.s = 4;
                attach(v2, 4);
                v2.d.d.gotoAndPlay(30);
                v2.lfra = fra;
                v2.spl = -10;
                v2.flyby = false;
                v2.dmg *= 3;
                if (haveEffect[106]) {
                  v2.dmg += 50;
                  v2._yscale = 123;
                  v2._xscale = 123;
                  if (haveEffect[106]) {
                    v2.col = 5;
                  }
                }
              } else {
                if (_root.bombnext) {
                  if (v2 != player) {
                    if (_root.bombnext == 2) {
                      v2.flir = true;
                      attach(v2, 497);
                      enf = 14 / enfget(v2.xbew, v2.ybew);
                      v2.xbew *= enf;
                      v2.ybew *= enf;
                      v2.s = 4;
                      v2.spl = -10;
                      v2.flyby = false;
                      colorit(v2, 1, 1, 1, 0, 0, 0);
                    } else {
                      v2.bomb = true;
                      attach(v2, 2);
                      colorit(v2, 1, 1, 1, 0, 0, 0);
                      v2.d.gotoAndStop('head');
                      v2.dy -= 10;
                      v2.dm += 1.2;
                      trg.d.d.d.gotoAndStop(29);
                    }
                    _root.bombnext = false;
                    _root.itemCharges = false;
                  }
                } else {
                  if (haveEffect[2]) {
                    if (haveEffect[169] && haveEffect[2] != 1 && !haveEffect[153] or haveEffect[149]) {
                      v2.xp = player.xp;
                      v2.yp = player.yp;
                      if (haveEffect[149]) {
                        trg.fire * 2;
                        trg.fire += 10;
                        v2.bomb = true;
                        v2.ipecacBomb = true;
                        v2.d._yscale = 160;
                        v2.d._xscale = 160;
                        f1 = Math.random() * 0.2 + 0.7;
                        v2.xbew *= f1;
                        v2.ybew *= f1;
                        v2.fd = 0.6;
                        v2.dm *= 0.7;
                        v2.dm -= 13;
                        colorit(v2, 0.5, 0.9, 0.4, 0, 0, 0);
                      }
                    } else {
                      if (haveEffect[153]) {
                        v2 = 0.07000000000000001;
                      } else {
                        v2 = 0.05;
                      }
                      v2.xbew -= yenf * v2;
                      v2.ybew += xenf * v2;
                      f1 = trg.xp + yenf * sob * v1;
                      f2 = trg.yp - xenf * sob * v1;
                      create(f1, f2, 0, xenf + yenf * v2, yenf - xenf * v2, 0, 2);
                      f1 = trg.xp + xenf;
                      f2 = trg.yp + yenf;
                      if (haveEffect[153]) {
                        v1 = 0.02;
                        v2 = 0.32;
                        create(f1 + yenf * v2 * 1.5, f2 - xenf * v2, 0, xenf + yenf * v1, yenf - xenf * v1, 0, 2);
                        create(f1 - yenf * v2 * 1.5, f2 + xenf * v2, 0, xenf - yenf * v1, yenf + xenf * v1, 0, 2);
                      } else {
                        create(f1, f2, 0, xenf, yenf, 0, 2);
                      }
                    }
                  }
                }
              }
            }
          }
          plox = 7 + trg.fire * 0.45;
          if (haveEffect[118]) {
            if (v2.bomb) {
              plo = 1;
              plox = 1;
              trg.d.d.d.d.gotoAndStop(1);
            } else {
              plox = 24;
            }
          }
          chaf = undefined;
          chaz = chaf;
        } else {
          if (trg.fire1 < 0) {
            trg.fire1 = 10;
            xenf = xxenf;
            yenf = yyenf;
            enf = enfget(xenf, yenf);
            enf = 10 / enf;
            xenf *= enf;
            yenf *= enf;
            xxenf = xenf;
            yyenf = yenf;
            xenf += trg.xbew * 0.6;
            yenf += trg.ybew * 0.6;
            enf = enfget(xenf, yenf);
            if (enf < 10) {
              enf = 10 / enf;
              xenf *= enf;
              yenf *= enf;
            }
            v1 = 0.3 + Math.random() * 0.2;
            if (haveEffect[2]) {
              v1 = 0.8;
              sob = 1;
            }
            f1 = trg.xp;
            f2 = trg.yp;
            e = 0;
            while (e < folz.length) {
              var v2 = folz[e];
              if (fra - v2.lfra > trg.fire1 + 3 && !v2.cat && !v2.mon && !v2.hol && !v2.ni && !v2.bum) {
                if (v2.maga) {
                  v2.outway = false;
                  v2.charge = true;
                  v2.xbew = xenf;
                  v2.ybew = yenf;
                  v2.xp = player.xp;
                  v2.yp = player.yp;
                  if (Math.abs(xenf) > Math.abs(yenf)) {
                    sideflip(xenf, v2.d);
                    v2.d.gotoAndStop(35);
                  } else {
                    if (yenf < 0) {
                      v2.d.gotoAndStop(36);
                    } else {
                      v2.d.gotoAndStop(37);
                    }
                  }
                  v2.lfra = fra + 80;
                  v2.dmg = 3.5;
                } else {
                  if (v2.baa != 5) {
                    v2.d.gotoAndStop(plo + 4);
                    v2.lfra = fra;
                    if (v2.laser) {
                      v2.d.gotoAndStop(plo + 45);
                      f1 = 1 / enfget(xenf, yenf);
                      v2.xpp = xenf * f1;
                      v2.ypp = yenf * f1;
                      laserDamage = 3;
                      lasershow(v2, 2);
                      _root.soundy('RedLightning_Zap_' + random(3) + '.mp', 60);
                    } else {
                      if (!llss) {
                        _root.soundy('Tears_Fire_' + random(3) + '.mp');
                      }
                      if (v2.dou) {
                        babymode = 2;
                      } else {
                        if (v2.baa > 1) {
                          babymode = v2.baa;
                        } else {
                          babymode = 1;
                        }
                      }
                      if (babymode == 8) {
                        f1 = [1, 2, 3, 4, 5, 6, 7];
                        babymode = f1[random(f1.length)];
                      }
                      f1 = v2.xp;
                      f2 = v2.yp;
                      f10 = belial;
                      belial = v2.dou;
                      if (babymode == 7) {
                        f3 = 0.2;
                        var v3 = create(f1, f2, 0, xenf + yenf * f3, yenf - xenf * f3, 0, 2);
                        v3.d._xscale *= 0.8;
                        v3.d._yscale *= 0.8;
                        babymode = 7;
                        f3 = -f3;
                        v3 = create(f1, f2, 0, xenf + yenf * f3, yenf - xenf * f3, 0, 2);
                        v3.d._xscale *= 0.8;
                        v3.d._yscale *= 0.8;
                      } else {
                        var v3 = create(f1, f2, 0, xenf, yenf, 0, 2);
                        v3.d._xscale *= 0.8;
                        v3.d._yscale *= 0.8;
                        if (v2.baa == 9) {
                          v3.xbew *= -1;
                          v3.ybew *= -1;
                        }
                      }
                      if (v2.baa == 11) {
                        v2.d.gotoAndStop(plo + 156);
                      } else {
                        if (v2.baa == 10) {
                          v2.d.gotoAndStop(plo + 165);
                        } else {
                          if (v2.baa == 9) {
                            v2.d.gotoAndStop(plo + 142);
                          } else {
                            if (v2.baa == 8) {
                              v2.d.gotoAndStop(plo + 120);
                            } else {
                              if (v2.baa == 7) {
                                v2.d.gotoAndStop(plo + 111);
                              } else {
                                if (v2.baa == 6) {
                                  v2.d.gotoAndStop(plo + 102);
                                } else {
                                  if (v2.baa == 4) {
                                    v2.d.gotoAndStop(plo + 68);
                                  } else {
                                    if (v2.baa == 3) {
                                      v2.d.gotoAndStop(plo + 59);
                                    } else {
                                      if (v2.meat) {
                                        v2.d.gotoAndStop(plo + 27);
                                      } else {
                                        if (v2.dou) {
                                          v2.d.gotoAndStop(plo + 13);
                                        }
                                      }
                                    }
                                  }
                                }
                              }
                            }
                          }
                        }
                      }
                      belial = f10;
                    }
                    if (!haveEffect[52]) {
                      ++e;
                    }
                  }
                }
              }
              ++e;
            }
            plox1 = 7 + trg.fire1 * 0.45;
          }
        }
        if (plox > 8 or _root.faceMode == 7 && !haveEffect[68] && !haveEffect[118]) {
          if (haveEffect[68] && haveEffect[59]) {
            trg.d.d.d.d.gotoAndStop(plo + 8);
          } else {
            trg.d.d.d.d.gotoAndStop(plo + 4);
          }
        } else {
          trg.d.d.d.d.gotoAndStop(plo);
        }
      }

      function chaxx() {
        f1 = 1;
        if (Math.abs(xenf) > Math.abs(yenf)) {
          yenf = 0;
          if (xenf < 0) {
            xenf = f1;
          } else {
            xenf = -f1;
          }
          trg.xpp = xenf;
          trg.ypp = yenf;
          return true;
        }
        xenf = 0;
        if (yenf < 0) {
          yenf = f1;
          trg.xpp = xenf;
          trg.ypp = yenf;
          return true;
        }
        yenf = -f1;
        trg.xpp = xenf;
        trg.ypp = yenf;
        return true;
      }

      function chaxy() {
        outgrid(trg.til);
        f3 = xenf;
        f4 = yenf;
        f5 = random(8);
        f1 = player.xp + player.xbew * f5;
        f2 = player.yp + player.ybew * f5;
      }

      function chaa(f9) {
        chaxy();
        if (enfcheckx(f3, f4, f1, f2, 200)) {
          if (f9 == 2) {
            f3 = true;
          } else {
            if (!f9) {
              f3 = linecheck(f3, f4, f1, f2);
            } else {
              f3 = linecheckxx(f3, f4, f1, f2);
            }
          }
          if (f3) {
            return chaxx();
          }
        }
      }

      function eyefly() {
        trg.xbew *= 0.7;
        trg.ybew *= 0.7;
        v1 = 1;
        if (trg.xbew > 0) {
          trg.xbew += v1;
        } else {
          trg.xbew -= v1;
        }
        if (trg.ybew > 0) {
          trg.ybew += v1;
        } else {
          trg.ybew -= v1;
        }
        v1 = 3;
        if (trg.xp > 580) {
          trg.xbew -= v1;
        }
        if (trg.xp < 60) {
          trg.xbew += v1;
        }
        if (trg.yp > 410) {
          trg.ybew -= v1;
        }
        if (trg.yp < 170) {
          trg.ybew += v1;
        }
      }

      function friends() {
        trg.damger = trg.s == 3 && (trg.alt && trg.fly or trg.meat or trg.charge or trg.ang or trg.bird or trg.blueFlies or trg.peeper or trg.ni or trg.hairball or trg.dad);
        trg.ggh = true;
        colorit(trg, 1, 1, 1, 0, 0, 0);
        trg.dou = false;
        if (trg.meat && trg.meat != 5) {
          if (trg.me2) {
            trg.meat = Math.min(4, haveEffect[73] - 4);
          } else {
            trg.meat = Math.min(4, haveEffect[73]);
          }
        }
        if (trg.stopi) {
        } else {
          if (trg.hairball) {
            enfcheck(trg.xp, trg.yp, player.xp, player.yp, 10000);
            f1 = 15 + _root.hairball * 2;
            enf = (Math.min(1.4, f1 - enf) / enf) * 0.07000000000000001;
            trg.xbew += xenf * enf;
            trg.ybew += yenf * enf;
            f1 = 0.87 + _root.hairball * 0.01;
            if (trg.d._currentframe != 149 or trg.d.d._currentframe == trg.d.d._totalframes) {
              trg.d.gotoAndStop(148);
              trg.d.d.gotoAndStop(_root.hairball);
            } else {
              trg.d.d.nextFrame();
              trg.d.d.d.gotoAndStop(_root.hairball);
            }
            trg.xbew *= f1;
            trg.ybew *= f1;
            trg.dmg = 3 + _root.hairball * 2;
            if (fra % 14 == 0) {
              trg.hh = [];
            }
          } else {
            if (trg.peeper) {
              if (random(4) == 0) {
                splater(trg.xp, trg.yp, trg.spl + 1 + random(10), Math.random() * 0.3 + 0.1);
              }
              trg.dmg = 8;
              if (fra % 14 == 0) {
                trg.hh = [];
              }
              trg.d.gotoAndStop(130);
              eyefly();
            } else {
              if (trg.meat > 2 or trg.bird or trg.blueFlies or trg.bum && ashut == 0 or trg.dad) {
                if (trg.blueFlies && trg.trg2 == undefined) {
                  trg.trg2 = player;
                }
                if (random(4) == 0 && !trg.bird && !trg.blueFlies && !trg.bum && !trg.dad) {
                  splater(trg.xp, trg.yp, trg.spl + 1 + random(10), Math.random() * 0.3 + 0.1);
                }
                trg.ggh = false;
                if (fra % 14 == 0) {
                  trg.hh = [];
                }
                if (trg.bum) {
                  if (trg.d._currentframe != 135) {
                    trg.d.gotoAndStop(134);
                  }
                } else {
                  if (trg.blueFlies) {
                    trg.ggh = true;
                    trg.dmg = 2 * baseDamage();
                    f12 = fra * 0.03;
                    if (haveEffect[112]) {
                      f12 *= 2;
                    }
                    f11 = (f12 + (blub / Math.max(1, ablub)) * 2) * Math.PI;
                    if (trg.trg2 == player && f11 > -100) {
                      trg.xpp = player.xp + Math.sin(f11) * 35;
                      trg.ypp = player.yp + Math.cos(f11) * 30;
                    } else {
                      if (trg.trg2 != undefined) {
                        trg2 = trg.trg2;
                        trg.xpp = trg2.xp;
                        trg.ypp = trg2.yp;
                      } else {
                        trg.xpp = trg.xp;
                        trg.ypp = trg.yp;
                      }
                    }
                    if (trg.trg2 == undefined) {
                    } else {}
                    ++blub;
                    ++blufb;
                    trg.d.gotoAndStop(128);
                  } else {
                    if (trg.dad) {
                      trg.ggh = true;
                      trg.dmg = 20;
                      trg.d.gotoAndStop(151);
                      if (trg.d.d._currentframe != 1) {
                        trg.d.d.nextFrame();
                      }
                      if (trg.d.d._currentframe >= 37) {
                        trg.d.d.gotoAndStop(1);
                      }
                      trg.bh = trg.d.d._currentframe > 10 && trg.d.d._currentframe < 33;
                      if (trg.bh) {
                        trg.fire = 100;
                      }
                    } else {
                      if (trg.bird) {
                        trg.ggh = true;
                        trg.dmg = 2;
                        if (trg.bird == 2) {
                          trg.d.gotoAndStop(171);
                        } else {
                          trg.d.gotoAndStop(83);
                        }
                      } else {
                        if (trg.meat == 5) {
                          trg.dmg = 7;
                          if (sk == 5) {
                            trg.d.gotoAndStop(80);
                          } else {
                            if (sk == 7) {
                              trg.d.gotoAndStop(81);
                            } else {
                              trg.d.gotoAndStop(79);
                            }
                          }
                          trg.sp = _root.playsp * 2;
                        } else {
                          if (trg.meat > 3) {
                            trg._yscale = 143;
                            trg._xscale = 143;
                            trg.dmg = 5.5;
                            trg.sp = 2.2;
                            trg.d.gotoAndStop(54);
                          } else {
                            trg.dmg = 3.5;
                            trg.sp = 1.8;
                            trg.d.gotoAndStop(54);
                          }
                        }
                      }
                    }
                  }
                }
                trg.outway = false;
                if (trg.trg2.dones) {
                  trg.trg2 = player;
                  trg.fire = 50 - trg.dmg * 5;
                }
                if (trg.trg2 == undefined or trg.trg2 == momHeart && !trg.trg2.bh) {
                  trg.trg2 = player;
                  trg.fire = 5;
                }
                trg2 = trg.trg2;
                if (trg2 == player) {
                  f1 = 80;
                } else {
                  f1 = 20;
                }
                --trg.fire;
                if (trg.blueFlies) {
                  if (trg.blueFlies) {
                    xenf = trg.xpp - trg.xp;
                    yenf = trg.ypp - trg.yp;
                  }
                  enf = enfget(xenf, yenf);
                  enf = Math.min(2, enf * 0.15) / enf;
                  xenf *= enf;
                  yenf *= enf;
                  trg.xbew += xenf;
                  trg.ybew += yenf;
                } else {
                  if (fra % 3 == 0 or trg.whaf == undefined) {
                    trg.whaf = !enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, f1) && trg.fire <= 0;
                  }
                  if (trg.whaf) {
                    if (trg.bird or trg.bum or trg.dad) {
                      xenf = trg2.xp - trg.xp;
                      yenf = trg2.yp - trg.yp;
                      enf = enfget(xenf, yenf);
                      if (trg.dad && enf < 30 && trg2 != player) {
                        if (trg.d.d._currentframe == 1) {
                          trg.d.d.nextFrame();
                          trg.stomps = random(3) + 1;
                        }
                      }
                      if (trg.dad) {
                        xenf += trg2.xbew * 5 - trg.xbew * 5;
                        yenf += trg2.ybew * 5 - trg.ybew * 5;
                        enf = enfget(xenf, yenf);
                      }
                      enf = 1 / enf;
                      xenf *= enf;
                      yenf *= enf;
                      trg.xbew += xenf;
                      trg.ybew += yenf;
                    } else {
                      pathfind(trg, trg2.xp, trg2.yp, trg.sp);
                    }
                  }
                }
                if (!trg.blueFlies && !trg.dad && trg.d._currentframe != 135) {
                  if (enfget(trg.xbew, trg.ybew) > 2) {
                    trg.d.d.gotoAndStop(2);
                    sideflip(trg.xbew, trg);
                    trg.d.d.he.gotoAndStop(5);
                  } else {
                    trg.d.d.he.gotoAndStop(1);
                    trg.d.d.gotoAndStop(1);
                  }
                }
                if (trg.d._currentframe == 135) {
                  trg.d.d.nextFrame();
                  _root.tex = trg.d.d._currentframe;
                  if (trg.d.d._currentframe == 10) {
                    emo();
                    _root.pickedUp[144] -= 3 + random(2);
                    f2 = 5.1022 + random(5) * 0.0001;
                    if (random(2) == 0) {
                      if (random(3) == 0) {
                        f2 = 5;
                      } else {
                        f2 = 5.03 + random(2) * 0.01;
                      }
                    } else {
                      if (random(3) != 0) {
                        if (random(2) == 0) {
                          f2 = 5.07;
                        } else {
                          f2 = 5.3;
                        }
                      } else {
                        f2 = 5.35;
                      }
                    }
                    spaw(trg.xp * 0.5 + player.xp * 0.5, trg.yp * 0.5 + player.yp * 0.5, 0, f2);
                  }
                  if (trg.d.d._currentframe == trg.d.d._totalframes) {
                    trg.d.gotoAndStop(134);
                  }
                }
                if (trg.bum) {
                  if (fra % 5 == 0) {
                    f13 = 200;
                    f6 = trg.xp;
                    f7 = trg.yp;
                    f2 = 0;
                    for (z in ball) {
                      trg2 = ball[z];
                      if (trg2.s == 5) {
                        if (!trg2.dones && trg2.d._currentframe == 2) {
                          f12 = enfcheck(trg2.xp, trg2.yp, f6, f7, f13);
                          if (f12 < f13) {
                            f13 = f12;
                            f2 = trg2;
                          }
                        }
                      }
                    }
                    if (f13 == 200 or f2.s != 5) {
                      trg.trg2 = player;
                    }
                    if (f2 && trg.trg2 != f2) {
                      trg.fire = 5;
                      trg.trg2 = f2;
                    }
                    if (f13 < 30 && trg2 != trg) {
                      trg2 = trg.trg2;
                      _root.pickedUp[144] += collectCoin(trg2);
                      trg2.d.d.gotoAndStop(2);
                      trg2.dones = true;
                    }
                    if (trg2 == player) {
                      f12 = enfcheck(trg2.xp, trg2.yp, f6, f7, 100);
                      if (f12 < 80) {
                        if (_root.pickedUp[144] > 5) {
                          trg.d.gotoAndStop(135);
                        }
                      }
                    }
                  }
                } else {
                  if (random(3) == 0 or !trg.blueFlies) {
                    if (ashut > 0 && (trg2 == player or trg.fire < 200) && (fra + trg.e) % 13 == 0) {
                      f2 = false;
                      if (random(2) == 0) {
                        f6 = player.xp;
                        f7 = player.yp;
                      } else {
                        f6 = trg.xp;
                        f7 = trg.yp;
                      }
                      f13 = 65 + trg.dmg * 15;
                      if (trg.blueFlies) {
                        f13 = 200;
                      }
                      for (z in ball) {
                        trg2 = ball[z];
                        if (trg2.s > 9 && !trg2.dones) {
                          if (enfcheck(trg2.xp, trg2.yp, f6, f7, f13)) {
                            if (trg2 != momHeart && !trg2.mom && trg2.satanPhase >= 3 or trg2.bh) {
                              f2 = trg2;
                            }
                          }
                        }
                      }
                      if (f2 && trg.trg2 != f2) {
                        trg.fire = 5;
                        trg.trg2 = f2;
                      }
                    }
                  }
                }
                if (trg.dad && trg.bh) {
                  trg.xbew *= 0.5;
                  trg.ybew *= 0.5;
                } else {
                  if (trg.bird or trg.dad) {
                    trg.xbew *= 0.9;
                    trg.ybew *= 0.9;
                  } else {
                    trg.xbew *= 0.8;
                    trg.ybew *= 0.8;
                  }
                }
              } else {
                if (trg.maga && trg.charge) {
                  if (mhity(trg.xp + trg.xbew, trg.yp + trg.ybew) or trg.charge > 1) {
                    killshit(ingrid(trg.xp, trg.yp));
                    if (trg.charge > 1) {
                      ++trg.charge;
                    } else {
                      trg.charge = 2;
                    }
                    trg.xbew *= 0.5;
                    trg.ybew *= 0.5;
                    if (trg.charge > 10) {
                      trg.charge = false;
                    }
                  }
                } else {
                  if (trg.fly or trg.meat or trg.ang or trg.ni) {
                    f1 = player.xp - 2;
                    f2 = player.yp - 4;
                    if (trg.alt) {
                      if (fra % 2 == 0) {
                        trg.hh = [];
                      }
                      if (trg.alt == 2) {
                        trg.d.gotoAndStop(128);
                        trg.dmg = 2;
                        f11 = fra * 0.013 * Math.PI;
                        if (haveEffect[112]) {
                          f11 *= 1.5;
                        }
                        trg.xp = f1 + Math.sin(f11) * 110;
                        trg.yp = f2 + Math.cos(f11) * 90;
                      } else {
                        trg.d.gotoAndStop(21);
                        trg.dmg = 5;
                        f11 = -fra * 0.02 * Math.PI;
                        if (haveEffect[112]) {
                          f11 *= 1.5;
                        }
                        trg.xp = f1 + Math.sin(f11) * 60;
                        trg.yp = f2 + Math.cos(f11) * 45;
                      }
                    } else {
                      if (trg.ni) {
                        trg.d.gotoAndStop(132);
                        trg.dmg = 15;
                        if (fra % 6 == 0) {
                          trg.hh = [];
                        }
                      } else {
                        if (trg.ang) {
                          trg.dmg = 7;
                          if (fra % 18 == 0) {
                            trg.hh = [];
                          }
                          trg.d.gotoAndStop(97);
                        } else {
                          if (trg.meat) {
                            trg.dmg = 7;
                            if (fra % 18 == 0) {
                              trg.hh = [];
                            }
                            if (trg.meat <= 1) {
                              trg.d.gotoAndStop(22);
                            } else {
                              f11 += 11;
                              trg.dou = true;
                              if (trg.lfra + 4 < fra) {
                                trg.d.gotoAndStop(plo + 23);
                              }
                              folz.push(trg);
                            }
                          } else {
                            trg.d.gotoAndStop(20);
                          }
                        }
                      }
                      flys.push(e);
                      f12 = fra * 0.03;
                      if (haveEffect[112]) {
                        f12 *= 2;
                      }
                      f11 = (f12 + ffly * fll) * Math.PI;
                      trg.xp = f1 + Math.sin(f11) * 25;
                      trg.yp = f2 + Math.cos(f11) * 20;
                      if (trg.fly) {
                        lff = trg;
                      }
                      if (trg.blueFlies) {
                      } else {
                        ++ffly;
                        if (ffly > 3) {
                          lff.done = true;
                        }
                      }
                    }
                    trg.xbew *= 0.8;
                    trg.ybew *= 0.8;
                  } else {
                    trg.outway = true;
                    f1 = (follow == player or follow.maga or follow.dou or follow.ba) && !trg.maga && !trg.bum && !trg.hol && !trg.cat && !trg.mon;
                    trg.baa = 0;
                    if (f1) {
                      trg.baa = 0;
                      var f11 = lastbb;
                      if (trg.ggho && trg.ggho != 2 && lastbbb != 11 && lastbb != 11) {
                        trg.baa = 11;
                        lastbb = 11;
                      } else {
                        if (trg.ggho == 2 && trg.ggho != true && lastbbb != 10 && lastbb != 10) {
                          trg.baa = 10;
                          lastbb = 10;
                        } else {
                          if (haveEffect[188] && lastbbb != 9 && lastbb != 9) {
                            trg.baa = 9;
                            lastbb = 9;
                          } else {
                            if (haveEffect[95] && lastbbb != 2 && lastbb != 2) {
                              trg.baa = 2;
                              lastbb = 2;
                            } else {
                              if (haveEffect[67] && lastbbb != 1 && lastbb != 1) {
                                trg.baa = 1;
                                lastbb = 1;
                              } else {
                                if (haveEffect[163] && lastbbb != 6 && lastbb != 6) {
                                  trg.baa = 6;
                                  lastbb = 6;
                                } else {
                                  if (haveEffect[167] && lastbbb != 7 && lastbb != 7) {
                                    trg.baa = 7;
                                    lastbb = 7;
                                  } else {
                                    if (haveEffect[174] && lastbbb != 8 && lastbb != 8) {
                                      trg.baa = 8;
                                      lastbb = 8;
                                    } else {
                                      if (haveEffect[99] && lastbbb != 3 && lastbb != 3) {
                                        trg.baa = 3;
                                        lastbb = 3;
                                      } else {
                                        if (haveEffect[113] && lastbbb != 5 && lastbb != 5) {
                                          trg.baa = 5;
                                          lastbb = 5;
                                        } else {
                                          if (haveEffect[100] && lastbbb != 4 && lastbb != 4) {
                                            trg.baa = 4;
                                            lastbb = 4;
                                          }
                                        }
                                      }
                                    }
                                  }
                                }
                              }
                            }
                          }
                        }
                      }
                      lastbbb = f11;
                    }
                    trg.laser = trg.baa == 2;
                    trg.dou = trg.baa == 1;
                    f1 = follow.xp;
                    f2 = follow.yp;
                    if (trg.baa == 9) {
                      f1 = 640 - player.xp;
                      f2 = 580 - player.yp;
                    }
                    if (trg.baa == 11) {
                      eyefly();
                    } else {
                      enfcheck(trg.xp, trg.yp, f1, f2, 100000);
                      f1 = 20;
                      f2 = enf < 75;
                      if (enf > f1) {
                        enf = ((enf - f1) / enf) * 0.1;
                        trg.xp -= xenf * enf;
                        trg.yp -= yenf * enf;
                      }
                    }
                    if (!trg.maga or f2) {
                      folz.push(trg);
                    } else {
                      trg.xbew *= 0.8;
                      trg.ybew *= 0.8;
                    }
                    if (trg.baa != 9) {
                      trg2 = follow;
                      follow = trg;
                    }
                    if (trg.bum) {
                      if (trg.d._currentframe != 135) {
                        trg.d.gotoAndStop(134);
                      }
                      sideflip(trg2.xp - trg.xp);
                    } else {
                      if (trg.hol) {
                        trg.d.gotoAndStop(126);
                      } else {
                        if (trg.maga) {
                          trg.d.gotoAndStop(34);
                        } else {
                          if (trg.cat) {
                            if (trg.cat == 2) {
                              trg.d.gotoAndStop(77);
                            } else {
                              trg.d.gotoAndStop(33);
                            }
                          } else {
                            if (trg.mon) {
                              if (trg.mon == 4) {
                                trg.d.gotoAndStop(95);
                              } else {
                                if (trg.mon == 3) {
                                  trg.d.gotoAndStop(75);
                                } else {
                                  if (trg.mon == 2) {
                                    trg.d.gotoAndStop(52);
                                  } else {
                                    trg.d.gotoAndStop(40);
                                  }
                                }
                              }
                              if (trg.d.d._currentframe > 1 or _root.monbb >= 1) {
                                trg.d.d.nextFrame();
                                if (trg.d.d._currentframe == 4) {
                                  _root.monbb = 0;
                                  switch (trg.mon) {
                                    case 4:
                                      f1 = 5.04; //Bomb Bag
                                      break;
                                    case 3:
                                      f1 = 5.010000003; //The Relic
                                      break;
                                    case 2:
                                      f1 = 5.010000002; //Little Chad
                                      _root.soundy('kiss_lips1.wav');
                                      break;
                                    case 1:
                                      f1 = 5.02; //Sack of Pennies
                                  }
                                  trg2 = spaw(trg.xp, trg.yp, 0, f1);
                                  if (trg.mon > 1 && trg.mon < 4) {
                                    trg2.col = trg.mon;
                                  }
                                }
                              }
                            } else {
                              trg.ba = true;
                              if (trg.lfra + 4 < fra) {
                                if (trg.baa == 5) {
                                  if (trg.plo == undefined) {
                                    trg.plo = 1;
                                  }
                                  trg.d.gotoAndStop(trg.plo + 84);
                                  if (fra % 10 == 0) {
                                    f2 = false;
                                    for (z in ball) {
                                      trg2 = ball[z];
                                      if (trg2.s > 9 && !trg2.dones) {
                                        if (enfcheck(trg2.xp, trg2.yp, trg.xp, trg.yp, 150)) {
                                          if (linecheckx(trg.xp, trg.yp, trg2.xp, trg2.yp)) {
                                            if (trg2.bh) {
                                              f2 = trg2;
                                            }
                                          }
                                        }
                                      }
                                    }
                                    if (f2 && trg.trg2 != f2) {
                                      trg.trg2 = f2;
                                      trg2 = trg.trg2;
                                    } else {
                                      trg2 = trg.trg2;
                                    }
                                    if (trg2 == player or trg2.dones) {
                                      trg.trg2 = undefined;
                                      trg2 = trg.trg2;
                                    }
                                    if (!f2) {
                                      if (!linecheckx(trg.xp, trg.yp, trg2.xp, trg2.yp)) {
                                        trg.trg2 = undefined;
                                        trg2 = trg.trg2;
                                      }
                                    }
                                    if (trg2) {
                                      xenf = trg.xp - trg2.xp;
                                      yenf = trg.yp - trg2.yp;
                                      enf = enfget(xenf, yenf);
                                      enf = 8 / enf;
                                      xenf *= enf;
                                      yenf *= enf;
                                      babymode = 5;
                                      if (Math.abs(xenf) > Math.abs(yenf)) {
                                        if (xenf < 0) {
                                          trg.plo = 2;
                                        } else {
                                          trg.plo = 4;
                                        }
                                      } else {
                                        if (yenf > 0) {
                                          trg.plo = 3;
                                        } else {
                                          trg.plo = 1;
                                        }
                                      }
                                      trg.d.gotoAndStop(trg.plo + 88);
                                      trg2 = create(trg.xp, trg.yp, 0, -xenf, -yenf, 0, 2);
                                    } else {
                                      trg.plo = 1;
                                    }
                                  }
                                } else {
                                  if (trg.baa == 11) {
                                    trg.d.gotoAndStop(plo + 152);
                                  } else {
                                    if (trg.baa == 10) {
                                      trg.d.gotoAndStop(plo + 161);
                                    } else {
                                      if (trg.baa == 9) {
                                        trg.d.gotoAndStop(plo + 138);
                                      } else {
                                        if (trg.baa == 8) {
                                          trg.d.gotoAndStop(plo + 116);
                                        } else {
                                          if (trg.baa == 7) {
                                            trg.d.gotoAndStop(plo + 107);
                                          } else {
                                            if (trg.baa == 6) {
                                              trg.d.gotoAndStop(plo + 98);
                                            } else {
                                              if (trg.baa == 4) {
                                                trg.d.gotoAndStop(plo + 64);
                                              } else {
                                                if (trg.baa == 3) {
                                                  trg.d.gotoAndStop(plo + 55);
                                                } else {
                                                  if (trg.laser) {
                                                    trg.d.gotoAndStop(plo + 41);
                                                  } else {
                                                    if (trg.dou) {
                                                      trg.d.gotoAndStop(plo + 9);
                                                    } else {
                                                      trg.d.gotoAndStop(plo);
                                                    }
                                                  }
                                                }
                                              }
                                            }
                                          }
                                        }
                                      }
                                    }
                                  }
                                }
                              }
                            }
                          }
                        }
                      }
                    }
                    trg.xbew *= 0.8;
                    trg.ybew *= 0.8;
                  }
                }
              }
            }
          }
        }
      }

      function rollSlots() {
        var v1 = 0;
        if (haveEffect[46]) {
          v1 = 3 + random(15);
        } else {
          v1 = 3 + random(21);
        }
        if (v1 >= 9 && (random(10) != 0 or portableSlot)) {
          ++v1;
        }
        if (v1 == 7 && random(3) == 0) {
          v1 = 10;
        }
        return v1;
      }

      function slotPrizes(f1) {
        switch (f1) {
          case 3:
            if (random(3) == 0) {
              _root.pickedUp[10] += 0.5;
              haveEffect[10] = _root.pickedUp[10];
              displayCornerMessage('Pretty Fly');
              emo();
            } else {
              f2 = 13;
              emo(true);
            }
            break;
          case 4:
            f2 = 5.04;
            break;
          case 5:
          case 6:
            f2 = 5;
            break;
          case 10:
          case 11:
          case 12:
            f2 = 5.02;
            f12 = Math.max(1, random(3));
            break;
          case 7:
            f2 = 5.03;
            break;
          case 8:
            f2 = 5.07;
            break;
          case 9:
            enf = enfcheck(trg.xp, trg.yp, player.xp, player.yp, f1);
            if (enf < f1) {
              enf = ((f1 - enf) / enf) * 0.4;
              player.xbew -= xenf * enf;
              player.ybew -= yenf * enf;
            }
            f2 = 5.1;
            trg.done = true;
            _root.soundy('boss1_explosions' + random(3) + '.wav', 80);
            break;
          default:
            if (portableSlot) {
              emo(true);
            }
        }
      }

      function actions2() {
        f2 = 0;
        f3 = fra % 3;
        if (f3 == 0) {
          f1 = 0.45;
        } else {
          if (f3 == 1) {
            f1 = 1;
          } else {
            f1 = 1.85;
          }
        }
        if (blackout == 2) {
          if (f1 == 1) {
            f2 = 30;
          }
          f1 *= 0.7;
          f1 -= 0.5;
        }
        bull = new flash.geom.ColorTransform();
        bull.redMultiplier = f1;
        bull.greenMultiplier = f1;
        bull.blueMultiplier = f1;
        bull.redOffset = f2;
        bull.greenOffset = f2;
        bull.blueOffset = f2;
        if (isaaaac) {
          f1 = (f1 - 1) * 0.1;
          bull.redMultiplier = f1 + 0.8;
          bull.greenMultiplier = f1 + 6;
          bull.blueMultiplier = f1 + 7.4;
          bull.redOffset = f2 + 20;
          bull.greenOffset = f2 + 20;
          bull.blueOffset = f2 + 20;
        }
        bull2 = new flash.geom.ColorTransform();
        if (fra % 2 == 0) {
          f3 = (fra % 6) / 2;
          if (f3 == 0) {
            f1 = 0.45;
          } else {
            if (f3 == 1) {
              f1 = 1;
            } else {
              f1 = 1.85;
            }
          }
          f1 = f1 * 0.2 + 0.85;
          if (blackout == 2) {
            f1 = 1;
          }
          bull2.redMultiplier = f1;
          bull2.greenMultiplier = f1;
          bull2.blueMultiplier = f1;
          bull2.redOffset = f2;
          bull2.greenOffset = f2;
          bull2.blueOffset = f2;
        }
        var v2 = new flash.geom.Transform(blorz);
        v2.colorTransform = bull2;
        magget = 0;
        momet = 0;
        wormet = 0;
        if (fra % 3 == 0) {
          for (e in levz) {
            if (levz[e] > 0 && levz[e] < 0.99) {
              levz[e] -= 0.1;
              if (levz[e] < 0) {
                levz[e] = 0;
              }
            }
          }
        }
        if (fra > 10) {
          _root.levit[_root.lev] = [];
        }
        ashut = shutdoor;
        shutdoor = 0;
        if (fra > 10) {
          _root.levcol[_root.lev] = 0;
        }
        follow = player;
        folz = [];
        ffly = 0;
        ablub = blub;
        blub = 0;
        _root.blueFlies = Math.min(blufb, 5);
        blufb = 0;
        if (fra > 40) {
          for (e in ref) {
            trg = ref[e];
            if (trg._currentframe < 5) {
              if (trg._parent._currentframe == 1) {
                if (random(5) == 0) {
                  enf = enfcheck(trg.xp, trg.yp, player.xp, player.yp, 160);
                  if (enf) {
                    _root.tex = enf;
                    f1 = 20 / enf;
                    if (linechecky(trg.xp - xenf * f1, trg.yp - yenf * f1, player.xp, player.yp)) {
                      if (fiz++ > 5) {
                        if (random(5) == 0) {
                          trg._parent.nextFrame();
                          fiz = 0;
                        }
                      }
                    }
                  }
                }
              } else {
                trg._parent.nextFrame();
              }
              if (trg._parent._currentframe == trg._parent._totalframes) {
                trg._parent.gotoAndStop(1);
              }
            } else {
              trg._parent.gotoAndStop(1);
            }
            if (trg._parent._currentframe == 3) {
              _root.tex = trg._parent._currentframe;
              enf = enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
              enf = enfget(xenf, yenf);
              enf = -5 / enf;
              xenf *= enf;
              yenf *= enf;
              create(trg.xp + xenf * 5, trg.yp + yenf * 5, 0, xenf, yenf, 0, 9);
            }
          }
        }
        if (anarch-- > 0) {
          if (anarch % 5 == 0) {
            trg2 = spaw(320, 280, random(300), 5.04);
            trg2.col = 3;
            if (analt == 5) {
              trg2.col = 5;
              trg2.dmg = 0;
            } else {
              if (analt) {
                attach(trg2, 502);
                trg2.s = 4;
                trg2.bolt = true;
                trg2.bh = false;
                if (analt >= 2) {
                  trg2.friend = true;
                  if (random(2) == 0 && analt == 2) {
                    trg3 = ball[random(ball.length)];
                    if (trg3.s > 10) {
                      trg2.xp = trg3.xp;
                      trg2.yp = trg3.yp;
                    }
                  }
                }
              }
            }
          }
        } else {
          analt = false;
        }
        if (killa) {
          for (z in levz) {
            if (killshit(z)) {
              killshit(z);
              killshit(z);
              killshit(z);
              killshit(z);
            }
          }
          killa = false;
        }
        splaz = false;
        if (beamer++ > 0) {
          f2 = Math.max(0, 20 - beamer) / 20;
          f3 = (1 - f2) * 255;
          colorit(_root, f2, f2, f2, f3, f3, f3);
          if (beamer > 25) {
            _root.fade = true;
            colorit(_root, 1, 1, 1, 0, 0, 0);
            newstart(false, true);
          }
        }
        if (momdown-- > 0) {
          if (_root.floorNum == 6) {
            f1 = Math.max(0, 1 - Math.abs(momdown - 50) / 40);
            f2 = 1 - f1;
            f3 = 150 * f1;
            colorit(_root, f2, f2, f2, f3, 0, 0);
            if (momdown == 50 && (!_root.SecretUnlocked[4] or _root.challenge > 0 && _root.challenge < 5) && _root.floorNum != 7) {
              _root.SecretUnlocked[4] = true;
              _root.SecretUnlocked[5] = true;
              _root.SecretUnlocked[6] = true;
              colorit(_root, 1, 1, 1, 0, 0, 0);
              _root.levz = undefined;
              moveon();
              _root.door = undefined;
              _root.gotoAndStop(9);
            }
          }
          splaz = true;
        }
        if (sacri-- > 0) {
          splaz = true;
        }
        if (splaz) {
          while (random(2) != 0) {
            f10 = random(15) + 2;
            xenf = crand(f10);
            yenf = crand(f10);
            trg2 = create(320 - xenf * 100, 280 - yenf * 100, 0, xenf, yenf, 0, 8);
            trg2.d._yscale = 140 + random(80);
            trg2.d._xscale = trg2.d._yscale;
            trg2.md -= random(20);
            trg2.fd += 0.5;
          }
        }
        helpss = helps;
        helps = 0;
        help = 0;
        for (e in ball) {
          trg = ball[e];
          if (trg.bosser && trg.dones) {
            trg.bosser = false;
            --bosser;
            if (bosser == 0 && !bossheart) {
              bossheart = true;
              f0 = 5.01;
              if (trg.s == 45 or trg.s == 78) {
                f1 = 320;
                f2 = 280;
              } else {
                f1 = trg.xp;
                f2 = trg.yp;
              }
              if (_root.bossRoom == _root.lev) {
                create(f1, f2, 0, crand(7), crand(7), 0, f0);
                if (_root.so.data.momKills < 6) {
                  create(f1, f2, 0, crand(7), crand(7), 0, f0);
                }
              }
              if (spezz) {
                trg2 = create(f1, f2, 0, crand(7), crand(7), 0, 5.01);
                if (spezz == 4 or spezz == 7) {
                  trg2.col = 3;
                }
              }
            }
          }
        }
        bosser = 0;
        lastbb = -1;
        lastbbb = -1;
        topz(1);
        if (decer.s == 4) {
          rply = player;
          player = decer;
        }
      }

      function deathscripts() {
        if (trg.s == 2 && trg.dones && !trg.wtfst) {
          trg.wtfst = true;
          if (haveEffect[104] && !trg.ba) {
            if (slugsp <= fra) {
              slugsp = fra + 5;
              xenf = trg.ybb;
              yenf = -trg.xbb;
              enf = enfget(xenf, yenf);
              f1 = trg.xp;
              f2 = trg.yp;
              if (mhity(f1, f2)) {
                f1 = trg.xpp;
                trg.xp = f1;
                f2 = trg.ypp;
                trg.yp = f2;
              }
              if (enf > 0) {
                enf = 8.5 / enf;
                xenf *= enf;
                yenf *= enf;
                trg2 = create(f1, f2, 0, xenf, yenf, 0, 2);
                trg3 = create(f1, f2, 0, -xenf, -yenf, 0, 2);
                trg2.wtfst = true;
                trg3.wtfst = true;
                trg2.bh = false;
                trg3.bh = false;
                trg3.dy = trg.dy;
                trg2.dy = trg.dy;
                trg3.dm = 1.2;
                trg2.dm = 1.2;
                trg2.d._xscale = trg.d._xscale;
                trg3.d._xscale = trg2.d._xscale;
                trg2.d._yscale = trg.d._yscale;
                trg3.d._yscale = trg2.d._yscale;
                trg2.dmg = trg.dmg;
                trg3.dmg = trg2.dmg;
                if (haveEffect[132]) {
                  trg2.coalSize = trg.coalSize;
                  trg3.coalSize = trg2.coalSize;
                }
              }
            }
          }
        } else {
          if (trg.s == 2 && !trg.dones) {
            trg.xbb = trg.xbew;
            trg.ybb = trg.ybew;
            trg.xpp = trg.xp;
            trg.ypp = trg.yp;
          }
        }
        if (trg.s == 25 && trg.alter == 2 && !trg.wtfst && trg.dones) {
          trg.wtfst = true;
          cirf(trg.xp, trg.yp, 8, 6);
        }
        if ((trg.s == 16 or trg.s == 22 or trg.s == 67) && trg.dones && !trg.wtfst) {
          trg.wtfst = true;
          if (trg.alter == 3) {
            trg = bombfail(trg.xp, trg.yp);
            trg.mug = true;
          } else {
            if (trg.alter == 2) {
              quadf(trg.xp, trg.yp, 8, 2);
              trg2 = spaw(trg.xp, trg.yp, 0, 5.04);
              trg2.col = 3;
            } else {
              if (trg.hp > -20) {
                flya();
              }
            }
          }
          if (trg.s == 67 && altboss && trg.specoz) {
            if (trg.specoz == 16) {
              f1 = 25;
            } else {
              if (trg.specoz) {
                f1 = 25.1;
              }
            }
            spaw(trg.xp, trg.yp, 20, f1);
            spaw(trg.xp, trg.yp, 20, f1);
          }
        }
        if (trg.s == 19 && altboss && trg.specoz && !trg.wtfst && trg.dones) {
          trg.wtfst = true;
          if (trg.specoz == 3) {
            f1 = 23;
          } else {
            if (trg.specoz == 16) {
              f1 = 25;
            } else {
              f1 = 5.02;
            }
          }
          spaw(trg.xp, trg.yp, 0, f1);
        }
        if (trg.s == 100 && altboss && trg.dones && !trg.wtfst) {
          trg.wtfst = true;
          boil();
          boil();
          boil();
        }
        if (trg.s == 101 && trg.dones && !trg.wtfst) {
          trg.wtfst = true;
          trg.done = true;
          momdown = 100;
        }
        if (trg.s == 91 && trg.dones && !trg.wtfst) {
          trg.wtfst = true;
          trg2 = spaw(trg.xp, trg.yp, 0, 25);
        }
        if (trg.frezz > 0) {
          --trg.frezz;
          trg.free = true;
        } else {
          if (trg.frezz < 1) {
            trg.free = false;
          }
        }
        if (trg.poisonDuration > 0) {
          --trg.poisonDuration;
          if (trg.poisonDuration % 20 == 1) {
            if (trg.s != 28 or altboss != 2) {
              hurt(trg, trg.poisonDamage);
            }
          }
        }
      }

      function actions1() {
        actions2();
        for (e in ball) {
          trg = ball[e];
          if ((hps[trg.s] / mux > 199 && !trg.goner && trg.s != 62 && trg.s != 96 && trg.s != 18 && trg.satanPhase != 5 or trg.s == 19 or trg.s == 20 or trg.s == 79 && (!trg.alt or altboss != 2) or trg.s == 82 or trg.s == 83 or trg.minb or trg.worm == 6 or trg.s == 67 or trg.s >= 71 && trg.s <= 77) && !trg.dones && !trg.sic && !trg.horse && !trg.weap && !momHeart or trg == momHeart) {
            ++bosser;
            trg.bosser = !trg.minb;
            trg.aboss = trg.bosser;
            if (trg.hp > trg.mhp) {
              trg.mhp = trg.hp;
            }
            help += trg.hp / trg.mhp;
            ++helps;
            f1 = 0;
            if (trg.s == 74) {
              f1 = 10;
            }
            if (trg.s == 75) {
              f1 = 4;
            }
            if (trg.s == 76) {
              f1 = 1;
            }
            if (trg.s == 71 && altboss) {
              f1 = 18;
            } else {
              if (trg.s == 71) {
                f1 = 12;
              }
            }
            if (trg.s == 72) {
              f1 = 2;
            }
            help += f1;
            helps += f1;
            bosser += f1;
            trg.hbar = true;
            mins = trg.minb or _root.lev != _root.bossRoom && _root.lev != _root.bossRoom2 && _root.lev != 166;
          }
          if ((trg.flyai or trg.s == 25 && !trg.alt) && !trg.dones) {
            ++flyshut;
          }
          if (trg.gosplash) {
            gosplash();
            trg.gosplash = false;
          }
          if ((trg.s == 61 or trg.s == 26 && trg.alter == 2) && trg.dones && !trg.wtfst) {
            trg.wtfst = true;
            if (trg.alter == 2 && trg.s == 61) {
              green();
            } else {
              quadf(trg.xp, trg.yp, 8);
            }
          }
          if (trg.s == 81 && trg.alter == 2) {		//Defeated Krampus
            if (trg.dones) {
              trg.alter = 0;
              _root.SecretUnlocked[64] = true;
              f0 = 5.1132;
              spaw(trg.xp, trg.yp, 0, f0);
            }
          }
          if (trg.minb) {
            if (!fonter) {
              fonter = true;
              f4 = ['Isaac', 'Magdalena', 'Cain', 'Judas', 'XXX', 'Eve', 'Samson'];
              f1 = ['Sloth', 'Lust', 'Wrath', 'Gluttony', 'Greed', 'Envy', 'Pride', 'Krampus'];
              f0 = trg.s - 46;
              if (trg.alter == 3) {
                f1 = ' vs Ultra Pride';
              } else {
                if (trg.alter == 2) {
                  f1 = ' vs Super ' + f1[f0];
                } else {
                  f1 = ' vs ' + f1[f0];
                }
              }
              displayBannerMessage(f4[_root.characterID] + f1);
            }
            if (trg.dones && helpss == 0 && !minsber) {
              minsber = true;
              if (trg.minb == 2) {
                f1 = 74;
                if (!_root.SecretUnlocked[10]) {
                  f1 = 64;
                }
                f1 = [5.3, 140, 5.07, 45, 5.04, 106, 5.01, 129, 5.02, f1, 5.04, 128, 5.3, 81];
              } else {
                f1 = [5.3, 42, 5.07, 13, 5.04, 37, 5.01, 15, 5.02, 64, 5.04, 49, 5.3, 65];
              }
              f0 = trg.s - 46;
              _root.minibossBeaten[f0] = true;
              if (_root.minibossBeaten[0] && _root.minibossBeaten[1] && _root.minibossBeaten[2] && _root.minibossBeaten[3] && _root.minibossBeaten[4] && _root.minibossBeaten[5] && _root.minibossBeaten[6]) {
                _root.SecretUnlocked[29] = true;
              }
              if (trg.minb == 3) { //Ultra Pride
                f0 = 5.07;
                trg2 = create(trg.xp, trg.yp, 0, 0, 0, 0, f0);
                trg2.col = 61;
                _root.SecretUnlocked[98] = true;
              } else {
                f0 *= 2;
                f2 = false;
                if (random(4) == 0 or trg.minb == 2 && random(7) == 0) {
                  f2 = true;
                }
                if (f2 && !_root.pickedUp[f1[f0 + 1]]) {
                  f0 = f1[f0 + 1];
                  f0 = 5.1 + f0 / 10000;
                } else {
                  f0 = f1[f0];
                }
                if (f0 == 5.04 && trg.s == 51) {			//Pride and Super Pride always drop a Troll Bomb.
                  trg2 = create(trg.xp, trg.yp, 0, 0, 0, 0, f0);
                  trg2.col = 3;
                } else {
                  if (f0 == 5.02) {							//Greed and Super Greed always drop 4-8 coins, which scatter.
                    f3 = 4 + random(5);
                    z = 0;
                    while (z < f3) {
                      f4 = random(5) + 2;
                      create(trg.xp, trg.yp, 0, crand(f4), crand(f4), 0, f0);
                      ++z;
                    }
                  } else {
                    if (f0 == 5.01 or f0 == 5.04) {			//Gluttony and Wrath drop two hearts/bombs.
                      f1 = crand(5);
                      f2 = crand();
                      create(trg.xp, trg.yp, 0, f1, f2, 0, f0);
                      create(trg.xp, trg.yp, 0, -f1, -f2, 0, f0);
                    } else {
                      spaw(trg.xp, trg.yp, 0, f0);
                    }
                  }
                }
              }
              trg.minb = false;
            }
          } else {
            if (trg.champion or trg.hallo) {
              if (trg.dones) {
                trg.champion = false;
                trg.hallo = false;
                f1 = Math.random();
                if (f1 < 0.4) {
                  f0 = 5.02;
                } else {
                  if (f1 < 0.6) {
                    f0 = 5.01;
                  } else {
                    if (f1 < 0.76 - _root.floorNum * 0.01) {
                      f0 = 5.03;
                    } else {
                      if (f1 < 0.8) {
                        if (random(2) == 0) {
                          f0 = 5.3;
                        } else {
                          f0 = 5.07;
                        }
                      } else {
                        if (f1 < 0.95) {
                          f0 = 5.04;
                        } else {
                          f0 = 5.05;
                        }
                      }
                    }
                  }
                }
                spaw(trg.xp, trg.yp, 0, f0);
              }
            }
          }
          if (trg.s == 51 && trg.tier <= 2 && trg.dones && !trg.wtfst) {
            ++helpss;
            helps = 1;
            trg.wtfst = true;
            f1 = crand(10);
            f2 = crand();
            trg2 = [];
            f3 = trg.s;
            if (trg.alter == 2) {
              f3 += 0.1;
            }
            trg2.push(create(trg.xp + f1, trg.yp + f2, 0, f1 * 0.4, f2 * 0.4, 0, f3));
            trg2.push(create(trg.xp - f1, trg.yp - f2, 0, -f1 * 0.4, -f2 * 0.4, 0, f3));
            if (trg.alter == 2 && trg.tier < 1 + random(2)) {
              trg2.push(create(trg.xp - f1, trg.yp - f2, 0, -f2 * 0.4, f1 * 0.4, 0, f3));
            }
            for (z in trg2) {
              trg2[z].fra = -100;
              trg2[z].tier = trg.tier + 1;
              trg2[z].hp /= trg.tier + 2;
              trg2[z]._yscale = 100;
              trg2[z]._xscale = 100;
              trg2[z].d.gotoAndStop(5 + trg.tier);
            }
          }
          if (trg.s == 76 && trg.dones && !trg.wtfst) {
            trg.wtfst = true;
            trg2 = create(trg.xp, trg.yp, 0, 0, 0, 0, 77);
            trg2.fra = -100;
          }
          if (trg.s == 73 && trg.dones && !trg.wtfst) {
            trg.wtfst = true;
            f33 = ingrid(trg.xp, trg.yp);
            f1 = levz[f33];
            if (altboss or f1 != 3) {
              f1 = 23;
              if (trg.specoz == 15) {
                f1 = 25;
              }
              if (altboss) {
                boil(true);
                boil(false);
              } else {
                trg2 = create(trg.xp, trg.yp, 0, 0, 0, 0, f1);
              }
              _root.soundy('summonsound.wav', 80);
              trg2.hp *= 0.75;
            }
          }
          if ((trg.s == 71 or trg.s == 72) && trg.dones && !trg.wtfst) {
            trg.wtfst = true;
            f1 = crand(20);
            f2 = crand();
            trg2 = [];
            f3 = trg.s + 1;
            trg2.push(create(trg.xp + f1, trg.yp + f2, 0, f1 * 0.2, f2 * 0.2, 0, f3));
            trg2.push(create(trg.xp - f1, trg.yp - f2, 0, -f1 * 0.2, -f2 * 0.2, 0, f3));
            if (trg.s == 71) {
              if (trg.specoz == 15 or altboss) {
                trg2.push(create(trg.xp + f2, trg.yp - f1, 0, 0, 0, 0, f3));
              } else {
                trg2.push(create(trg.xp + f2, trg.yp - f1, 0, f2 * 0.2, -f1 * 0.2, 0, f3));
                trg2.push(create(trg.xp - f2, trg.yp + f1, 0, -f2 * 0.2, f1 * 0.2, 0, f3));
              }
            }
            for (z in trg2) {
              trg2[z].fra = -100;
              trg2[z].d.gotoAndStop(2 + (f3 - 71) * 3);
            }
          }
          if (trg.s == 57 && trg.dones && !trg.wtfst) {
            trg.wtfst = true;
            f1 = crand(10);
            f2 = crand();
            if (trg.alter == 2) {
              f3 = 40;
            } else {
              f3 = 32;
            }
            create(trg.xp + f1, trg.yp + f2, 0, 0, 0, 0, f3);
            create(trg.xp - f1, trg.yp - f2, 0, 0, 0, 0, f3);
          }
          if (trg.s == 79 && altboss && !trg.wtfst && trg.dones) {
            trg.wtfst = true;
            quadf(trg.xp, trg.yp, 10, true);
          }
          if ((trg.s == 80 or trg.s == 94) && !trg.wtfst && trg.dones && trg.hp > -20) {
            trg.wtfst = true;
            f1 = player.yp - trg.yp;
            f2 = trg.xp - player.xp;
            enf = enfget(f1, f2);
            if (enf > 0) {
              enf = 10 / enf;
              f1 *= enf;
              f2 *= enf;
            } else {
              f1 = crand(10);
              f2 = crand(10);
            }
            if (trg.s == 94) {
              f3 = 85;
            } else {
              f3 = 18;
            }
            trg2 = create(trg.xp + f1, trg.yp + f2, 0, f1, f2, 0, f3);
            trg3 = create(trg.xp - f1, trg.yp - f2, 0, -f1, -f2, 0, f3);
            trg2.fra = -10;
            trg3.fra = -10;
          }
          deathscripts();
          if (trg.uncol < fra) {
            specialColoring(trg);
          }
          if (trg.s <= 9) {
            if (!trg.dones) {
              switch (trg.s) {
                case 3:
                  friends();
                  break;
                case 2:
                  if (trg.fra + 2 < fra) {
                    trg.bh = true;
                  }
                  if (trg.ipecacBomb) {
                    trg.ggh = trg.dy > -50;
                    trg.bh = trg.ggh;
                    trg.ggh = !trg.ggh;
                    if (trg.yp < 230) {
                      trg.ggh = false;
                    }
                    if (trg.yp > 420) {
                      trg.ggh = false;
                    }
                    if (trg.xp > 540) {
                      trg.ggh = false;
                    }
                    if (trg.xp < 80) {
                      trg.ggh = false;
                    }
                  }
                  if (haveEffect[5] && !trg.ba) {
                    trg2 = player;
                    enf = enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, 500);
                    enf = 0.6 / enf;
                    trg.xbew -= xenf * enf;
                    trg.ybew -= yenf * enf;
                    trg.xbew *= 0.98;
                    trg.ybew *= 0.98;
                    trg.fd = -0.045;
                  }
                  if (haveEffect[132] && !trg.ba && !haveEffect[114]) {
                    if (trg.coalSize++ < 150) {
                      trg.dmg += 0.14;
                      trg.d._xscale += 1;
                      trg.d._yscale += 1;
                    }
                  }
                  if (haveEffect[3] && !trg.ba or trg.ba == 4 or trg.ba == 11) {
                    if (trg.trg2 == undefined or trg.trg2.dones or trg.trg2.xp <= 0) {
                      if ((fra + trg.e) % 9 == 0) {
                        f1 = trg.xp + trg.xbew * 5;
                        f2 = trg.yp + trg.ybew * 5;
                        siz = 100;
                        for (i in ball) {
                          trg2 = ball[i];
                          if (trg2.s > 9 && !trg2.dones && !trg.hh[trg2.e]) {
                            enf = enfcheck(f1, f2, trg2.xp, trg2.yp, siz);
                            if (enf) {
                              if (trg2.pos >= 3 && (trg2 != momHeart or trg2.bh)) {
                                siz = enf;
                                trg.trg2 = trg2;
                              }
                            }
                          }
                        }
                        if (trg.trg2 != undefined) {
                          trg2 = trg.trg2;
                          if (linecheckx(trg.xp, trg.yp, trg2.xp, trg2.yp)) {
                            trg.gonuts = true;
                          }
                        }
                      }
                    } else {
                      if (trg.trg2 != undefined) {
                        trg2 = trg.trg2;
                        if ((fra + trg.e) % 5 == 0) {
                          if (linecheckx(trg.xp, trg.yp, trg2.xp, trg2.yp)) {
                            trg.gonuts = true;
                          }
                        }
                        if (trg2.dones or trg.hh[trg.trg2.e]) {
                          trg.trg2 = undefined;
                          trg.gonuts = false;
                        } else {
                          if (trg.gonuts && random(2) == 0) {
                            enf = enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, 100);
                            if (enf > 0) {
                              enf = 2 / enf;
                              trg.xbew -= xenf * enf;
                              trg.ybew -= yenf * enf;
                              if (haveEffect[182] && !trg.ba) {
                                trg.xbew *= 0.7;
                                trg.ybew *= 0.7;
                              } else {
                                trg.xbew *= 0.85;
                                trg.ybew *= 0.85;
                              }
                            }
                          }
                        }
                      }
                    }
                  }
                  if (haveEffect[59] && trg.trg2 == undefined && !trg.ba) {
                    outgrid(ingrid(trg.xp, trg.yp));
                    trg.nuts *= 0.5;
                    if (trg.dir) {
                      trg.nuts += Math.abs(trg.xbew) * 0.02;
                      trg.xbew /= 0.8 + trg.nuts;
                      trg.xbew += (xenf - trg.xp) * 0.3;
                    } else {
                      trg.nuts += Math.abs(trg.ybew) * 0.02;
                      trg.ybew /= 0.8 + trg.nuts;
                      trg.ybew += (yenf - trg.yp) * 0.3;
                    }
                  }
                case 9:
                  if (trg.s == 9 && (!trg.bomb or blackout == 2) && trg.sss != 68 && !trg.hom && trg.sss != 100 && (trg.sss != 101 or !altboss)) {
                    var v2 = new flash.geom.Transform(trg);
                    v2.colorTransform = bull;
                    if (isaaaac) {
                      trg.colo = bull;
                      trg.spl = 10;
                    }
                  }
                  if (random(16) == 0 or trg.spll) {
                    splater(trg.xp, trg.yp, trg.spl + 1 + random(10), Math.random() * 0.3 + 0.1);
                  }
                  if (trg.hom) {
                    enf = enfcheck(trg.xp + trg.xbew * 5, trg.yp + trg.ybew * 5, player.xp, player.yp, 100);
                    if (enf > 0) {
                      enf = enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
                      enf = 1.4 / enf;
                      trg.xbew -= xenf * enf;
                      trg.ybew -= yenf * enf;
                      trg.xbew *= 0.92;
                      trg.ybew *= 0.92;
                    }
                  }
                case 8:
                  if (trg.s == 8) {
                    if (random(3) == 0) {
                      splater(trg.xp, trg.yp, trg.spl + 1 + random(10), (Math.random() * 0.3 + 0.1) * trg.d._xscale / 100);
                    }
                  }
                case 7:
                  if (!trg.knife) {
                    trg.dm *= 0.9;
                    trg.dm += 0.1;
                    if (trg.fd) {
                      trg.dm += trg.fd;
                    }
                    trg.dy += trg.dm;
                    trg.d._y = trg.dy;
                    if (trg.dy > -5) {
                      if (trg.s == 2) {
                        trg.wtfst = true;
                      }
                      if ((trg.s == 8 or trg.s == 7) && !mhit(trg.xp, trg.yp)) {
                        maxx = new flash.geom.Matrix();
                        maxx.translate(trg.xp, trg.yp);
                        maxx.scale(hdx, hdx);
                        if (trg.colo) {
                          gut.draw(trg, maxx, trg.colo);
                        } else {
                          if (trg.s == 8) {
                            gut.draw(trg, maxx, bloc);
                          } else {
                            gut.draw(trg, maxx);
                          }
                        }
                        trg._visible = false;
                      }
                      if (random(2) == 0) {
                        _root.soundy('splatter0' + random(3) + '.wav');
                      }
                      trg.d.gotoAndStop('groundhit');
                      trg.dones = true;
                    }
                  }
                  if (trg.s == 9) {
                    if (trg.nog-- <= 0) {
                      if (trg.dy < -50) {
                        trg.bh = false;
                        trg.ggh = true;
                      } else {
                        trg.ggh = false;
                        trg.bh = true;
                      }
                    }
                  }
                  break;
                case 5:
                  if (trg.d.d.d._currentframe == 25 && trg.d.d._currentframe == 3 && fra > 35) {
                    switch (trg.d._currentframe) {
                      case 1:
                        _root.soundy('Meat_Feet_slow0.wav');
                        break;
                      case 2:
                        if (trg.col == 3) {
                          _root.soundy('dimedrop.wav');
                        } else {
                          if (trg.col == 1) {
                            _root.soundy('pennydrop.mp');
                          } else {
                            _root.soundy('nickeldrop.mp');
                          }
                        }
                        break;
                      case 3:
                        _root.soundy('Key_drop0.wav');
                        break;
                      case 7:
                        if (trg.col < 7) {
                          _root.soundy('Fetus_Jump_' + random(2) + '.wav');
                        } else {
                          _root.soundy('scamper' + random(2) + '.wav');
                        }
                    }
                  }
                  if (fra % 30 == 0) {
                    if (trg.d._currentframe == 8) {
                      for (a in ball) {
                        trg2 = ball[a];
                        if (trg != trg2 && trg2.s == 5 && trg2.d._currentframe < 8) {
                          enf = enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, 40);
                          if (enf) {
                            if (enfget(trg2.xbew, trg2.ybew) < 0.2) {
                              if (enf == 0) {
                                xenf = crand(1);
                                yenf = crand(1);
                                enf = 1;
                              }
                              enf = 2 / enf;
                              trg2.xbew -= xenf * enf;
                              trg2.ybew -= yenf * enf;
                            }
                          }
                        }
                      }
                    }
                  }
                  if (trg.col == 10 && trg.d._currentframe == 8) {
                    trg.xbew = 0;
                    trg.ybew = 0;
                  }
                  if (trg.d._currentframe == 15) {
                    if (haveEffect[64] && (trg.d.d._currentframe < 5 or trg.d.d._currentframe == 12 or trg.d.d._currentframe == 13)) {
                      f1 = trg.d.d.d._currentframe;
                      trg.d.d.gotoAndStop(trg.d.d._currentframe + 4);
                      trg.d.d.d.gotoAndStop(f1);
                    }
                  }
                  if (trg.spin) {
                    if (trg.d.d._currentframe == 2 && trg.d.d.d._currentframe == 17) {
                      _root.soundy('slot touched.wav');
                    }
                    if (trg.d.d._currentframe == 42 && trg.d.d.d._currentframe == 35) {
                      _root.soundy('shellgame' + random(2) + '.wav');
                    }
                    if (trg.d.d._currentframe == 42 && trg.d.d.d._currentframe == 35) {
                      _root.soundy('shellgame' + random(2) + '.wav');
                    }
                    if (trg.d.d._currentframe >= 42 && trg.d.d.d._currentframe == 65) {
                      _root.soundy('shell game.wav');
                    }
                    if (trg.d.d._currentframe == 40 && trg.d.d.d._currentframe == 20) {
                      _root.soundy('bum shoot off.wav');
                    }
                    f1 = trgnextd(trg.d.d.d, true);
                    if (trg.d.d._currentframe == 42) {
                      trg.d.d.d.it.gotoAndStop(trg.shellGuyItem + 1);
                    }
                    if (f1 == 43 or f1 == 44 or f1 == 45) {
                      trg.spin = false;
                    } else {
                      if (f1 == 42) {
                        lastspin = fra + 50;
                        trg.wtf = false;
                      } else {
                        if (f1 == 37) {
                          if (trg.col == 31) {
                            if (random(4 - haveEffect[46]) == 0) {	//Demon Beggar
                              trg.d.d.gotoAndStop(38);
                            } else {
                              trg.d.d.gotoAndStop(36);
                              trg.spin = false;
                            }
                            trg.wtf = false;
                          } else {
                            if (trg.col++ > random(2) + random(4) + random(4)) {	//Regular Beggar
                              if (haveEffect[46]) {		//Lucky foot makes money
                                ++trg.col;				//count twice.
                              }							//OR NOT
                              trg.col = 2 + random(2);	//BECAUSE IT'S COMPLETELY POINTLESS
                              trg.d.d.gotoAndStop(38);
                            } else {
                              trg.d.d.gotoAndStop(36);
                              trg.spin = false;
                            }
                            trg.col = Math.min(9, trg.col);
                            trg.wtf = false;
                          }
                        } else {
                          if (f1 == 2) {	//Slot Machine
                            if (random(50) == 0 && chestopen == undefined) {	//2% chance of exploding outright.
                              chestopen = trg;
                              trg.d.d.gotoAndStop(30);
                              trg.spin = false;
                              trg.busted = true;
                              _root.soundy('boss1_explosions' + random(3) + '.wav', 80);
                            } else {
                              trg.d.d.gotoAndStop(rollSlots());
                              trg.wtf = false;
                            }
                          } else {
                            if (f1 > 2 && (trg.col == 41 or trg.col <= 1)) {
                              trg.spin = false;
                            }
                          }
                        }
                      }
                    }
                    if (trg.d.d.d._currentframe > 15 && trg.d.d._currentframe > 2 && !trg.wtf) {
                      if (trg.col != 1 or trg.d.d.d._currentframe > 36) {
                        lastspin = fra + 12;
                        trg.wtf = true;
                        f1 = trg.d.d._currentframe;
                        f2 = 0;
                        f12 = 1;
                        if (trg.col == 41 && f1 > 2 && f1 < 24) {
                          f1 = 0.65 - haveEffect[46];
                          if (Math.random() < f1) {
                            fortunes = ['Look to la Luna', 'Don\'t Leave The House Today', 'We will all die one day', 'You are throwing your life away', 'Go outside!', 'Give Up!', 'You will die alone', 'Ask again later', 'WAKE UP', 'you are worshiping a sun god', 'Stay asleep', 'Marry and Reproduce', 'Question authority', 'think for yourself', 'Steven lives', 'Bring him the photo'];
                            displayBannerMessage(fortunes[random(.length)]);
                          } else {
                            if (random(20) == 0) {
                              chestopen = trg;
                              trg.d.d.gotoAndStop(30);
                              trg.spin = false;
                              trg.busted = true;
                              _root.soundy('boss1_explosions' + random(3) + '.wav', 80);
                            } else {
                              if (random(30) == 0) {
                                f2 = 5.1;
                              } else {
                                if (random(3) == 0) {
                                  f2 = 5.3;
                                } else {
                                  if (random(3) == 0) {
                                    f2 = 5.010000003;
                                  } else {
                                    f2 = 5.35;
                                  }
                                }
                              }
                            }
                          }
                        } else {
                          slotPrizes(f1);
                          switch (f1) {
                            case 43:	//Shell 1...
                            case 44:	//Shell 2...
                            case 45:	//or Shell 3?
                              if (random(3) == 0 or random(3) == 0 && haveEffect[46]) {
                                f2 = 5.01 + trg.shellGuyItem * 0.01;
                                if (f2 == 5.02) {
                                  f12 = 2 + random(2);
                                } else {
                                  f12 = Math.max(random(3), 2);
                                }
                                if (trg.shellGuyItem == 5) {
                                  f2 = 5.1009;
                                }
                              } else {
                                f2 = 18;
                                _root.soundy('boss2intro_errorbuzz.wav');
                              }
                              break;
                            case 42:
                              break;
                            case 38: //Beggars
                              if (trg == flox && trg.minb != 3) {
                                flox = undefined;
                              }
                              trg.spin = false;
                              if (trg.col == 31) {
                                if (random(2) == 0) {
                                  if (random(2) == 0) {
                                    f2 = 5.07;							//Pill		25%
                                  } else {
                                    f2 = 5.3;							//Tarot		25%
                                  }
                                } else {
                                  if (random(4) == 0) {
                                    f2 = 5.35;							//Trinket	12.5%
                                  } else {
                                    f2 = 5.1;							//Item		37.5%
                                  }
                                }
                              } else {
                                f2 = 5.1022 + random(5) * 0.0001;
                                if (random(2) == 0) {
                                  if (random(3) == 0) {
                                    f2 = 5;								//Heart		16.66%
                                  } else {								//Bomb		16.66%
                                    f2 = 5.03 + random(2) * 0.01;		//Key		16.66%
                                  }
                                } else {
                                  if (random(2) == 0) {
                                    if (random(2) == 0) {
                                      f2 = 5.1022 + random(5) * 0.0001;	//HP Up		12.5%
                                    } else {
                                      f2 = 5.3;							//Tarot		12.5%
                                    }
                                  } else {
                                    f2 = 5.1;							//Item		25%
                                  }
                                }
                              }
                              trg.d.d.gotoAndStop(36);
                              break;
                            case 33:	//Blood Donation Machines
                              if (random(15) == 0) {
                                f2 = 5.1;
                                trg.done = true;
                                _root.soundy('boss1_explosions' + random(3) + '.wav', 80);
                              } else {
                                f2 = 5.02;
                                f12 = Math.max(1, random(3));
                                if (haveEffect[75]) {
                                  ++f12;
                                }
                                _root.soundy('bloodbank spawn' + random(2) + '.wav', 90);
                              }
                              break;
                            case 3:
                              break;
                            case 4:
                            case 5:
                            case 6:
                            case 10:
                            case 11:
                            case 12:
                            case 7:
                            case 8:
                            case 9:
                              break;
                            case 37:
                            default:
                              emo(true);
                          }
                        }
                        if (f2 > 0) {
                          if (f1 < 33) {
                            emosound = false;
                          }
                          if (f2 < 7 && f1 != 33) {
                            emo();
                          }
                          emosound = true;
                          if (f1 < 33) {
                            _root.soundy('slotspawn' + random(3) + '.wav');
                          }
                          if (f2 >= 5.1 && trg.col > 1 && trg.col != 41 && f2 < 5.3) {
                            beggar = true;
                            if (trg.col == 31) {
                              beggar = 2;
                            }
                            trg2 = spaw(trg.xp, trg.yp + 80, 0, f2);
                            if (trg.col == 41) {	//Fortune Teller Machines
                              trg.empty = true;
                              trg.d.d.gotoAndStop(30);
                              trg2.it = 158;
                            } else {
                              trg.empty = true;
                              trg.dones = true;
                              trg.d.d.gotoAndStop(40);
                            }
                          } else {
                            i = 0;
                            while (i < f12) {
                              f13 = 0;
                              while (f13++ < 10) {
                                if (f1 >= 43 && f1 <= 45) {
                                  yenf = 4 + crand(2);
                                  xenf = (f1 - 44) * 4 + crand(2);
                                  f14 = xenf * 5;
                                  f15 = 5;
                                } else {
                                  xenf = crand(5);
                                  yenf = crand(5) * 0.2 + 3;
                                  f14 = 0;
                                  f15 = 0;
                                }
                                if (linecheckx(trg.xp + f14, trg.yp + f15, trg.xp + xenf * 7, trg.yp + yenf * 7)) {
                                  f13 = 1000;
                                }
                              }
                              var trg2 = create(trg.xp + f14, trg.yp, 0, xenf, yenf, 0, f2);
                              trg2.alt = 2;
                              if (f2 == 18) {
                                trg2.fra = -10;
                                trg2.xp += xenf * 4;
                              }
                              if (f2 == 5.1) {
                                if (trg.col == 41) {
                                  trg2.d.col = 41;
                                  trg2.it = 158;
                                  trg.done = true;
                                } else {
                                  if (trg.col == 1) {
                                    trg2.it = 119;
                                    if (random(2) == 0 && !haveEffect[135]) {
                                      trg2.it = 135;
                                    }
                                    trg2.alt = 3;
                                  } else {
                                    trg2.it = 18;
                                  }
                                }
                                trg2.fra -= 15;
                                trg2.d.d.gotoAndStop(44);
                              }
                              ++i;
                            }
                          }
                        }
                      }
                    }
                  }
                  if (trg.alt) {
                    if (trg.alt > 4) {
                      trg.d.d.al.gotoAndStop(trg.alt);
                    } else {
                      if (trg.alt == 3) {
                        trg.d.d.al.gotoAndStop(4);
                      } else {
                        if (trg.alt == 2) {
                          trg.d.d.al.gotoAndStop(3);
                        } else {
                          trg.d.d.al.gotoAndStop(2);
                        }
                      }
                    }
                  }
                  if (fra - trg.fra > 25) {
                    trg.bh = true;
                  }
                  if (trg.it > 0) {
                    f1 = trg.it / 100;
                  } else {
                    f1 = 0;
                  }
                  if (trg.d._currentframe == 4) {
                    if (trg.fail == undefined) {
                      trg.fail = 0;
                    }
                    if ((trg.col == 3 or trg.col == 5) && trg.fail++ > 60) {
                      trg.done = true;
                      trg2 = bombfail(trg.xp, trg.yp);
                      trg2.col = trg.col;
                    }
                  }
                  if (trg.d._currentframe == 9) {
                    trg.nod = true;
                    trg.swapDepths(300 + e);
                    if (enfcheck(trg.xp, trg.yp, player.xp, player.yp, 50) && !trg.open) {
                      trg.d.d.gotoAndStop(1);
                    } else {
                      trg.open = true;
                      if (trg.d.d._currentframe != 23) {
                        trg.d.d.nextFrame();
                      }
                    }
                  } else {
                    if (trg.d._currentframe == 10) {
                      trg.d.d.nextFrame();
                      trg.d.d.d.d.gotoAndStop(trg.it);
                      if (trg.empty) {
                        trg.d.d.d.gotoAndStop(21);
                      }
                    } else {
                      if (trg.d._currentframe == 15) {
                        f1 = trg.d.d._currentframe / 10 + f1 / 100;
                        trg.d.d.d.gotoAndStop(trg.it);
                      }
                    }
                  }
                  if (trg.col) {
                    f1 += trg.col / 10000000;
                  }
                  f1 = trg.d._currentframe + f1;
                  if (!trg.empty or trg.spin) {
                    _root.levit[_root.lev].push([f1, trg.xp, trg.yp]);
                  }
                  if (trg.d._currentframe >= 5 && trg.d._curretnframe != 7) {
                    trg.xbew *= 0.8;
                    trg.ybew *= 0.8;
                  }
                  if (trg.d._currentframe >= 8 && !trg.busted && (trg.d._currentframe != 10 or !trg.alt)) {
                    trg.xp = trg.xpp;
                    trg.yp = trg.ypp;
                  }
                  trg.xbew *= 0.965;
                  trg.ybew *= 0.965;
                  if (!trg.empty) {
                    f1 = trg.d._currentframe;
                    if (f1 == 7) {
                      if (trg.col < 7) {
                        f1 = 8;
                      }
                    } else {
                      if (f1 == 8) {
                        f1 = 9;
                      } else {
                        if (f1 == 9) {
                          f1 = 0;
                        }
                      }
                    }
                    f2 = _root.levcol[_root.lev];
                    if (f1 == 1 && f2 < 5) {
                      f2 = 0;
                    }
                    if (f2 == 1 && f1 < 5) {
                      f1 = 0;
                    }
                    _root.levcol[_root.lev] = Math.max(f2, f1);
                  }
                  break;
                case 4:
                  if (trg.bolt) {	//Crack The Sky
                    if (trgnextd(trg.d, true)) {
                      trg.done = true;
                    }
                    if (trg.d._currentframe > 5 && trg.d._currentframe < 28) {
                      if (fra % 3 == trg.e % 3) {
                        for (a in ball) {
                          trg2 = ball[a];
                          if (trg2.s == 1 or trg2.s > 10) {
                            if (enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, 30)) {
                              if (trg2 == player) {
                                if (!trg.friend) {
                                  playerhurt(1, 65);
                                }
                              } else {
                                if (trg2.s != 102) {
                                  if (trg.friend) {
                                    hurt(trg2, 20);
                                  } else {
                                    hurt(trg2, 2);
                                  }
                                }
                              }
                            }
                          }
                        }
                      }
                    }
                  } else {
                    if (trg.flir) {
                      if (trgnextd(trg.d, false)) {
                        trg.done = true;
                      } else {
                        nofun = true;
                        for (a in ball) {
                          trg2 = ball[a];
                          if ((fra + trg2.e) % 5 == 0 && trg2.s > 8) {
                            if (enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, 43)) {
                              hurt(trg2, 23);
                              if (!f3 && trg2.firs + 10 <= fra) {
                                trg2.firs = fra;
                                _root.soundy('Firedeath_hiss.wav', Math.min(100, 50 + trg.hp * 5));
                              }
                            }
                          }
                        }
                      }
                      trg.xbew *= 0.95;
                      trg.ybew *= 0.95;
                    } else {
                      if (trg.decoy) {
                        decoy = undefined;
                        if (trg.d._currentframe != 7) {
                          trg.dones = true;
                        }
                      }
                      if (_root.spacebarItem == 97) {	//Remote Detonator
                        if (trg.d._currentframe == 1) {
                          if (trg.d.d._currentframe == 10) {
                            trg.d.d.gotoAndStop(1);
                          }
                        }
                      }
                      if (haveEffect[125] or haveEffect[52] && haveEffect[3]) {	//Bobby-Bomb or Dr. Fetus/Spoon Bender
                        if (trg.trg2 == undefined or trg.trg2.dones or trg.trg2.xp <= 0) {
                          if (fra % 3 == 0) {
                            f1 = trg.xp + trg.xbew * 5;
                            f2 = trg.yp + trg.ybew * 5;
                            siz = 150;
                            for (i in ball) {
                              trg2 = ball[i];
                              if (trg2.s > 9 && !trg2.dones && !trg.hh[trg2.e]) {
                                enf = enfcheck(f1, f2, trg2.xp, trg2.yp, siz);
                                if (enf) {
                                  siz = enf;
                                  trg.trg2 = trg2;
                                }
                              }
                            }
                            if (trg.trg2 != undefined) {
                              trg2 = trg.trg2;
                              if (linecheckx(trg.xp, trg.yp, trg2.xp, trg2.yp)) {
                                trg.gonuts = true;
                              }
                            }
                          }
                        } else {
                          if (trg.trg2 != undefined) {
                            trg2 = trg.trg2;
                            if ((fra + trg.e) % 5 == 0) {
                              if (linecheckx(trg.xp, trg.yp, trg2.xp, trg2.yp)) {
                                trg.gonuts = true;
                              }
                            }
                            if (trg2.dones or trg.hh[trg.trg2.e]) {
                              trg.trg2 = undefined;
                              trg.gonuts = false;
                            } else {
                              if (trg.gonuts) {
                                enf = enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, 100);
                                if (enf > 0) {
                                  enf = 0.5 / enf;
                                  trg.xbew -= xenf * enf;
                                  trg.ybew -= yenf * enf;
                                  trg.xbew *= 0.95;
                                  trg.ybew *= 0.95;
                                }
                              }
                            }
                          }
                        }
                      }
                      if (trg.d._currentframe == 1) {
                        trg.d.d.nextFrame();
                      }
                      if (fra - trg.fra > 30) {
                        trg.ph = false;
                      }
                      if (fra - trg.fra > 15) {
                        trg.bh = true;
                      }
                      if (fra - trg.lfra > 3 && !trg.nex) {
                        trg.nex = true;
                        nextbo = true;
                      }
                      if (!trg.empty) {
                        _root.levit[_root.lev].push([-100, trg.xp, trg.yp]);
                      }
                      trg.xbew *= 0.95;
                      trg.ybew *= 0.95;
                      trg.d.d.p.gotoAndStop(trg.col);
                    }
                  }
              }
            }
          } else {
            if (fra - trg.fra < 10 && !trg.dones && trg.s != 84 && trg.s != 101) {
              trg.d.gotoAndStop(4);
            }
            if (firecheck(trg)) {
              if (fra - trg.lastfir >= 10) {
                trg.lastfir = fra;
                hurt(trg, 8);
              }
            }
            if (trg.s != 42 && trg.s != 44 && !trg.dones && trg.s != 33 && trg.s != 37 && !trg.weap && !trg.goner && trg.s != 96 && !trg.efly && (trg.s != 18 && trg.s != 85 or justnow < 10)) {
              ++shutdoor;
            }
            if (trg.d._currentframe == 4 && !trg.apf && !trg.dones) {
              trg.xbew *= 0.45;
              trg.ybew *= 0.45;
              trgnextd();
              if (trg.s == 10) {
                if (trg.gonuts) {
                  trg.d.d.h.gotoAndStop(2);
                }
              }
              if (trg.s == 30) {
                f1 = trg.hp / hps[trg.s];
                trg.d.d.h.d.gotoAndStop(Math.max(1, 14 - Math.round(f1 * 13)));
              }
              if (trg.s == 11) {
                if (!trg.bnuts) {
                  trg.d.bb._visible = false;
                  trg.d.d.bb._visible = false;
                }
              }
            }
            if (trg.s == 30) {
              trg.xp = trg.xpp;
              trg.yp = trg.ypp;
            }
            if ((trg.d._currentframe != 4 or trg.apf) && !trg.dones) {
              if (freez > 0 or trg.frezz > 0 or trg.s < 4 && sloww) {
                trg.xbew *= 0.8;
                trg.ybew *= 0.8;
                trg.free = true;
              } else {
                if (trg.flyai) {
                  switch (trg.s) {
                    case 14:
                      if (trgnextd(trg.d.hx.d)) {
                        trg.d.gotoAndStop(1);
                      }
                      if (!haveEffect[9]) {
                        firemode(200, 4);
                      }
                      if (trg.fire > 0) {
                        trg.xbew *= 0.8;
                        trg.ybew *= 0.8;
                        trg.xbb *= 0.7;
                        trg.ybb *= 0.7;
                      }
                    case 80:
                    case 18:
                      if (trg.duke) {
                        ++dukes;
                        if (duke.dones or duke.send) {
                          trg.duke = false;
                          if (enfcheck(trg.xp, trg.yp, duke.xp, duke.yp, 260)) {
                            f1 = 18 / enf;
                            trg.xbew += xenf * f1;
                            trg.ybew += yenf * f1;
                          }
                        } else {
                          if (fra % 3 == 1) {
                            if (enfcheck(trg.xp, trg.yp, duke.xp, duke.yp, 260)) {
                              f3 = duked;
                              f1 = (absmax(enf - f3, 5) / enf) * 0.5;
                              f2 = 0.2 / (2 + Math.abs(f3 - enf));
                              trg.xbew -= xenf * f1;
                              trg.ybew -= yenf * f1;
                              trg.xbew += yenf * f2;
                              trg.ybew -= xenf * f2;
                              trg.xbew += duke.xbew * 0.4;
                              trg.ybew += duke.ybew * 0.4;
                            }
                          }
                        }
                      }
                    case 13:
                    case 61:
                      trg.outway = fra % 2 == 0;
                      if (fra % 3 == 0) {
                        if (haveEffect[9] && trg.s == 18 && !trg.duke) {
                          trg.s = 13;
                          attach(trg, 13);
                          trg.ggh = true;
                        }
                        if (haveEffect[9] && trg.s == 80) {
                          trg.s = 13;
                        }
                        if (!trg.duke) {
                          if (trg.s == 18 or trg.s == 61 or haveEffect[9] or trg.s == 80) {
                            trg.goshit = 1;
                          } else {
                            f1 = trg.xp + crand(Math.random() * Math.random() * 240);
                            f2 = trg.yp + crand();
                            f3 = ingrid(f1, f2);
                            v1 = levz[f3];
                            if (v1 > 1 && v1 < 1.8) {
                              trg.goshit = f3;
                            }
                          }
                        }
                      }
                      if (trg.goshit > 0 && fra % 2 == 0) {
                        outgrid(trg.goshit);
                        v1 = 30;
                        if (trg.s == 18 or trg.s == 61 or trg.s == 80 or haveEffect[9]) {
                          xenf = player.xp;
                          yenf = player.yp;
                          v1 = 25;
                        }
                        if (trg.s == 61 or trg.d._xscale > 110) {
                          v1 = 15;
                        }
                        xenf = trg.xp - xenf;
                        yenf = (trg.yp - yenf) / 2;
                        enf = enfget(xenf, yenf);
                        if (enf > v1) {
                          v1 = Math.min(0.6, (enf - v1) * 0.04) * 2;
                        } else {
                          if (random(1000) == 0) {
                            if (killshit(trg.goshit)) {
                              trg.s = 14;
                              trg.alter = 1;
                              if (random(3) == 0) {
                                trg.alter = 2;
                              }
                              attach(trg, 14);
                            }
                          }
                          v1 = 0;
                        }
                        enf = v1 / enf;
                        if (trg.s != 18 && trg.s != 61 && trg.s != 80) {
                          trg.xbb *= 0.7;
                          trg.ybb *= 0.7;
                        }
                        if (trg.die) {
                          trg.xbew *= 0.9;
                          trg.ybew *= 0.9;
                        }
                        trg.xbew -= xenf * enf;
                        trg.ybew -= yenf * enf;
                      }
                      if (trg.s == 18) {
                        f0 = 0.3;
                      } else {
                        f0 = 0.17;
                      }
                      if (fra % 4 == 1) {
                        trg.xbb += crand(f0 * 2);
                        trg.ybb += crand();
                        trg.xbb *= 0.8;
                        trg.ybb *= 0.8;
                        f1 = levz[ingrid(trg.xp, trg.yp)];
                        f1 = f1 >= 1 && f1 != 3;
                        f2 = levz[ingrid(trg.xp + trg.xbb * 16, trg.yp + trg.ybb * 16)];
                        f2 = f2 >= 1 && f2 != 3;
                        if ((f1 or f2) && !(f1 && f2)) {
                          trg.xbb *= 0.5;
                          trg.ybb *= 0.5;
                        } else {
                          if (f1 && !f2) {
                            trg.xbb *= 1.3;
                            trg.ybb *= 1.3;
                          }
                        }
                      }
                      trg.ph = fra % 3 == 2;
                      if (trg.ph) {
                        if (!trg.duke) {
                          v1 = 0.06;
                          if (trg.yp < 230) {
                            trg.ybb += v1;
                          }
                          if (trg.yp > 420) {
                            trg.ybb -= v1;
                          }
                          if (trg.xp > 540) {
                            trg.xbb -= v1;
                          }
                          if (trg.xp < 80) {
                            trg.xbb += v1;
                          }
                        }
                        trg.xbew += trg.xbb * 2;
                        trg.ybew += trg.ybb * 2;
                        trg.xbew *= 0.6;
                        trg.ybew *= 0.6;
                      }
                  }
                } else {
                  smarts();
                }
              }
            }
          }
        }
        if (rply) {
          player = rply;
          rply = undefined;
        }
        tip(1);
        if (helps >= 1) {
          mhelps = Math.max(helps, mhelps);
          if (satanBoss.satanPhase == 1 or satanBoss.satanPhase == 2) {
            --mhelps;
            help -= 1;
          }
          help /= mhelps;
          _root.hud.bar.bar._xscale = 100 * help;
          _root.hud.bar._visible = true;
          if (mins) {
            _root.hud.bar.gotoAndStop(3);
            _root.hud.bar.bar._xscale *= 0.5600000000000001;
          } else {
            _root.hud.bar.gotoAndStop(1);
          }
        } else {
          _root.hud.bar.gotoAndStop(2);
          _root.hud.bar._visible = false;
        }
      }

      function green(f11, f12) {
        trg2 = bossfire(1, !f12, 10);
        trg2.bomb = true;
        trg2.d._yscale = 160;
        trg2.d._xscale = 160;
        if (trg.s != 43) {
          trg2.xbew *= 0.55;
          trg2.ybew *= 0.55;
        }
        if (f12) {
          f1 = Math.random() + 0.6;
          trg2.xbew *= f1;
          trg2.ybew *= f1;
        }
        trg2.fd -= 0.3;
        trg2.dm *= 0.7;
        trg2.dm -= 13;
        if (trg.s == 87) {
          trg2.fd -= 0.3;
          trg2.dm += 10;
        }
        if (trg.s == 64 or trg.s == 43 or trg.s == 82) {
          trg2.xp -= trg.d._xscale * 0.2;
          trg2.pois = true;
          trg2.spl = 30;
          if (trg.d._currentframe < 7 or trg.s == 82) {
            trg2.dy -= 27;
          }
        }
        if (trg.s == 82 or trg.s == 78) {
          trg2.pois = 4;
          trg2.spl = 0;
        } else {
          if (f11 == 2) {
            colorit(trg2, 0.2, 0.2, 0.2, 0, 0, 0);
          } else {
            if (!f11) {
              colorit(trg2, 0.4, 2, 0.5, 0, 0, 0);
            }
          }
        }
        if (trg.s == 62) {
          trg2.dy -= 40;
        }
        return trg2;
      }

      function boiler(f1, f2) {
        if (f1) {
          if (!trg.boss && !trg.s == 88 or random(50) == 0) {
            if ((enfcheck(trg.xp, trg.yp, player.xp, player.yp, 230) or random(4) == 0) && (trg.alter != 3 or ashut < 8 && random(ashut) == 0)) {
              trg.d.gotoAndStop(5);
            } else {
              trg.d.gotoAndStop(2);
            }
          } else {
            trg.d.d.gotoAndStop(1);
          }
          trg.fire = 0;
        } else {
          if (f2) {
            if (trg.fire++ == 10) {
              if (enfcheck(trg.xp, trg.yp, player.xp, player.yp, 250 - Math.random() * 20) && !trg.boss) {
                boil(true);
              } else {
                boil(false);
              }
            }
          }
        }
      }

      function boil(f1) {
        if (trg.alter == 3 or trg.c2 or trg.col == 31 or trg.s == 67 or trg.s == 73 or trg.s == 28 or trg.s == 64 or trg.s >= 100 or trg.s == 46) {
          if (trg.s == 88 or trg.s == 30) {
            _root.soundy('boil hatch.wav');
          }
          if (bigone) {
            f8 = 94;
          } else {
            f8 = 85;
          }
          if (trg.s == 28) {
            trg2 = spaw(xenf, yenf, 10, f8);
          } else {
            if (!f1) {
              trg2 = spaw(trg.xp, trg.yp, 100, f8);
            } else {
              trg2 = spaw(player.xp * 0.5 + trg.xp * 0.5, player.yp * 0.5 + trg.yp * 0.5, 70, f8);
            }
          }
          trg2.xpp = trg2.xp;
          trg2.ypp = trg2.yp;
          trg2.xp = trg.xp;
          trg2.yp = trg.yp;
          xenf = trg2.xpp - trg2.xp;
          yenf = trg2.ypp - trg2.yp;
          f1 = enfget(xenf, yenf);
          f1 = f2 / f1;
          f1 = 0.04;
          trg2.xbew = xenf * f1;
          trg2.f1 = trg2.xbew;
          trg2.ybew = yenf * f1;
          trg2.f2 = trg2.ybew;
          trg2.fra = 0;
          trg2.d.gotoAndStop(5);
          trg2.apf = false;
          trg2.df = -8;
          trg2.bh = false;
          trg.fire = -100;
        } else {
          if (trg.alter == 2) {
            trg.fire = -50;
            green(false, f1);
            _root.soundy('heartout.wav', 70);
          } else {
            bossfire(3 + random(2), f1, 10);
          }
        }
      }

      function braz() {
        for (z in ball) {
          trg2 = ball[z];
          if (trg2.s > 10 && trg2 != trg) {
            if (enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, 60)) {
              hurt(trg2, 100);
            }
          }
        }
      }

      function spih() {
        var v1 = spaw(player.xp, player.yp, 50, 29.3);
        v1.fra = 0;
        v1.xpp = v1.xp;
        v1.ypp = v1.yp;
        v1.xp = trg.xp;
        v1.yp = trg.yp;
        v1.d.gotoAndStop(2);
        v1.d.d.gotoAndStop(5);
        tgr2.apf = true;
        v1.f1 = 100;
      }

      function bawssmart() {
        switch (trg.s) {
          case 32:
            if (fra % 3 == 0) {
              splater(trg.xp, trg.yp + 8, 1 + random(10), Math.random() * 0.5 + 0.2);
            }
            markhere(trg);
            if (!trg.gogo) {
              randrunx(0.75);
              trg.xbew *= 0.85;
              trg.ybew *= 0.8;
              if ((fra + trg.e) % 7 == 0) {
                trg.gogo = chaa();
              }
            } else {
              if (trg.gh) {
                trg.gogo = false;
                trg.ypp = undefined;
                trg.xpp = trg.ypp;
              } else {
                trg.xbew *= 0.8;
                trg.ybew *= 0.8;
                trg.xbew += trg.xpp;
                trg.ybew += trg.ypp;
                outgrid(trg.til);
                if (Math.abs(trg.xbew) > Math.abs(trg.ybew)) {
                  trg.yp *= 0.9;
                  trg.yp += yenf * 0.1;
                } else {
                  trg.xp *= 0.9;
                  trg.xp += xenf * 0.1;
                }
              }
            }
            if (ashut < 5) {
              f11 = (fra + trg.e) % 12 == 0;
              f2 = (fra + trg.e) % 12 == 6;
            } else {
              if (ashut < 10) {
                f11 = (fra + trg.e) % 18 == 0;
                f2 = (fra + trg.e) % 18 == 9;
              } else {
                f11 = (fra + trg.e) % 24 == 0;
                f2 = (fra + trg.e) % 24 == 12;
              }
            }
            if (f11 or enfget(trg.xbew, trg.ybew) > 3 && f2) {
              trg2 = parc('bloo', trg.xp, trg.yp, 0, 123);
              if (trg.champion) {
                trg2.specol = trg.specol;
                trg2.champion = true;
                specialColoring(trg2);
              } else {
                colorit(trg2, trg.rrr, trg.rrr, trg.rrr, 0, 0, 0);
              }
            }
            break;
          case 88:
            trg.xbew *= 0.75;
            trg.ybew *= 0.75;
            if (trg.d._currentframe < 3) {
              randrun();
              walkframe(2);
              sideflip(trg.xbew);
              boiler(true);
            } else {
              trgnextd();
              boiler(false, true);
            }
            break;
          case 30:
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            f1 = trg.hp / hps[trg.s];
            if (f1 >= 1) {
              trgnextd();
              boiler(trg.d._currentframe == 1, trg.d._currentframe == 5);
            } else {
              trg.fire = 0;
              trg.hp += trg.hppp * 1.2;
              if (trg.boss) {
                trg.hppp += 0.01;
              } else {
                trg.hppp += 0.02;
              }
              if (trg.alter == 3) {
                trg.hppp *= 0.8;
              }
              trg.hppp *= 0.9;
              trg.d.gotoAndStop(1);
              trg.d.hx.gotoAndStop(trg.alter);
              trg.d.hx.d.gotoAndStop(Math.max(1, 14 - Math.round(f1 * 13)));
            }
            break;
          case 91:
            if (trg.hpp == undefined) {
              trg.hpp = 0;
              trg.hppp = 0;
            }
            trg.xbew *= 0.77;
            trg.ybew *= 0.77;
            if (fra % 5 == 0) {
              v1 = (1 - trg.hp / trg.mhp) * 10;
              if (trg.hpp < v1) {
                ++trg.hpp;
                trg.d.b.d._xscale = 100 - v1 * 4;
                trg.d.b.d._yscale = trg.d.b.d._xscale;
                trg.d.b.sh._yscale = trg.d.b.d._yscale + 30;
                trg.d.b.sh._xscale = trg.d.b.d._yscale * 2.5 + 50;
                sideflip(player.xp - trg.xp);
                trg.d.d.play();
                if (trg.d.d._currentframe == 1) {
                  _root.soundy('Wheezy_Cough_' + random(3) + '.mp', 100);
                }
              }
            } else {
              if (trg.d.d._currentframe == 1 && trg.d._currentframe == 1) {
                sideflip(trg.xbew * 5);
              } else {
                if (trg.d.d._currentframe == 9 && trg.d._currentframe == 1) {
                  while (trg.hpp > trg.hppp) {
                    trg.hppp += 1 + Math.random();
                    if (ashut < 7) {
                      ++ashut;
                      xenf = (player.xp - trg.xp) * 0.1 + crand(10);
                      yenf = (player.yp - trg.yp) * 0.1 + crand(10);
                      create(trg.xp, trg.yp, 0, xenf, yenf, 0, 14);
                    }
                  }
                }
              }
            }
            if (random(100) == 0) {
              xenf = crand(10);
              yenf = crand(10);
              if (ashut < 10) {
                create(trg.xp, trg.yp, 0, xenf, yenf, 0, 18);
              }
            }
          case 25:
            if (trg.duke) {
              ++dukes;
            }
            if (trg.alt) {
              trg.nobomb = true;
              trg.d.gotoAndStop(9);
              splater(trg.xp, trg.yp, 1 + random(10), Math.random() * 0.3 + 0.3);
              if (helpss <= 0 or slug == undefined) {
                trg.dones = true;
              }
            }
            if (trg.alter == 2) {
              trg.nobomb = true;
            }
            if (haveEffect[9]) {
              f1 = 0.25;
            } else {
              f1 = 0.45;
            }
            if (trg.ybew > 0) {
              f2 = f1;
            } else {
              f2 = -f1;
            }
            if (trg.xbew > 0) {
              f1 = f1;
            } else {
              f1 = -f1;
            }
            trg.xbew *= 0.9;
            trg.ybew *= 0.9;
            trg.xbew += f1;
            trg.ybew += f2;
            break;
          case 102:
            if (trris + 45 + random(100) <= fra && random(20) == 0 && trg.state == 0) {
              trris = fra;
              _root.soundy('Scared_Whimper_' + random(3) + '.mp', 100);
            }
            isaaaac = true;
            f1 = Math.round(((trg.mhp - trg.hp) / trg.mhp) * 3 - 0.5);
            if (trgnextd(undefined, true)) {
              if (trg.d._currentframe == 4) {
                trg.d.gotoAndStop(7);
              } else {
                trg.d.gotoAndStop(1);
              }
            }
            if (trg.d._currentframe == 1) {
              if (trg.state < f1) {
                trg.state = f1;
                f2 = [0, 10, 7, 3];
                trg.d.gotoAndStop(f2[f1]);
              } else {
                f2 = [1, 5, 8];
                trg.d.gotoAndStop(f2[f1]);
              }
            }
            trg.xp = trg.xpp;
            trg.yp = trg.ypp;
            trg.xbew *= 0.6;
            trg.ybew *= 0.6;
            if (trg.isaacRetaliation && trg.state != 2) {
              trg.isaacRetaliation = false;
              bossfire(1, true);
            }
            if (altboss && random(60) == 0 && ashut < 20) {
              trg2 = create(trg.xp, trg.yp, 0, crand(10), crand(10), 0, 18);
              trg2.die = true;
              trg2.outway = true;
              trg2.fra = -20;
            }
            if (trg.state == 2) {
              if (trg.fire-- < 0) {
                if (random(10) == 0) {
                  anarch = 10;
                  analt = true;
                  trg.fire = 40;
                } else {
                  if (random(10) == 0 && ashut < 5) {
                    trg.fire = 120;
                    i = 0;
                    while (i < 2) {
                      spaw(trg.xp, trg.yp, 100, 38.1);
                      ++i;
                    }
                  }
                }
              }
            }
            switch (trg.d._currentframe) {
              case 7:
                if (trg.d.d._currentframe == 17) {
                  _root.soundy('superholy.wav');
                }
                break;
              case 10:
                if (trg.d.d._currentframe == 20) {
                  _root.soundy('Holy.mp');
                }
                break;
              case 1:
              case 5:
              case 8:
                if (random(60) == 0) {
                  f2 = [2, 6, 9];
                  trg.fire = 40;
                  trg.d.gotoAndStop(f2[trg.state]);
                }
                break;
              case 2:
                if (trg.d.d._currentframe == 3) {
                  cirf(trg.xp, trg.yp + 20, 10, 12);
                  _root.soundy('thumbs down.wav', 50);
                }
                break;
              case 6:
                if (trg.d.d._currentframe == 6) {
                  cirf(trg.xp, trg.yp, 10, trg.d._currentframe * 0.666);
                  _root.soundy('thumbsup.wav');
                }
                break;
              case 9:
                if (trg.d.d._currentframe == 17) {
                  _root.soundy('Powerup2.mp3');
                }
                if (trg.d.d._currentframe == 19) {
                  cirf(trg.xp, trg.yp, 10, trg.d._currentframe * 0.666);
                }
            }
            break;
          case 101:
            if (altboss) {
              spidboss = true;
            }
            if (trgnextd(undefined, true)) {
              f4 = 3;
              if (altboss) {
                --f4;
              }
              if (trg.d._currentframe == 7) {
                if (trg.goner) {
                  trg.done = true;
                } else {
                  if (trg.stomps++ < f4 or random(7) == 0) {
                    trg.d.d.gotoAndStop(1);
                  } else {
                    trg.d.gotoAndStop(5);
                  }
                }
              } else {
                if (trg.d._currentframe == 4) {
                  trg.d.gotoAndStop(7);
                } else {
                  trg.d.gotoAndStop(1);
                }
              }
            }
            trg.bh = (trg.d._currentframe != 4 or trg.d.d._currentframe < 21) && (trg.d._currentframe != 5 or trg.d.d._currentframe > 6) && (trg.d._currentframe != 7 or trg.d.d._currentframe > 11 && trg.d.d._currentframe < 27) && (trg.d._currentframe != 6 or trg.d.d._currentframe < 6 && trg.d.d._currentframe > 73);
            _root.tex = trg.bh;
            if (trg.d._currentframe == 5 && trg.d.d._currentframe == 9 or trg.d._currentframe == 7 && trg.d.d._currentframe == 9) {
              trg.dmg = 300;
              gosplash();
              if (trg.d._currentframe == 5) {
                _root.soundy('Hellboss_Groundpound_' + random(2) + '.wav', 70);
              } else {
                _root.soundy('ForestBoss_Stomps' + random(3) + '.wav', 100);
              }
              if (trg.d._currentframe == 5) {
                quadf(trg.xp, trg.yp, 10, true);
              }
              if (altboss) {
                trg2 = parc('bloo', trg.xp, trg.yp);
                trg2._xscale *= 2;
                trg2._yscale = trg2._xscale;
                colorit(trg2, 0, 0, 0, 255, 255, 255);
              }
            }
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            switch (trg.d._currentframe) {
              case 3:
                if (trg.d.d._currentframe == 18) {
                  if (altboss) {
                    spih();
                  }
                }
                if (trg.d.d._currentframe == 20) {
                  trg.yp += 15;
                  if (!altboss) {
                    boil();
                    boil();
                    if (random(2) == 0) {
                      boil();
                    }
                  }
                  _root.soundy('Boss_Spit_Blob_Barf.mp', 100);
                  trg.yp -= 15;
                }
                break;
              case 1:
                if (random(20) == 0) {
                  f2 = [4, 6, 6];
                  if (ashut < 4) {
                    f2.push(3, 3);
                  }
                  f1 = f2[random(f2.length)];
                  trg.stomps = 0;
                  trg.d.gotoAndStop(f1);
                }
                break;
              case 6:
                f1 = trg.d.d._currentframe;
                f2 = f1 - 16;
                f3 = 10;
                f2 %= f3;
                if (f2 == 0 && f1 < f3 * 4) {
                  if (trg.stomps != 3 or !altboss) {
                    trg2 = spaw(trg.xp, trg.yp, random(400), 101);
                    trg2.goner = true;
                    trg2.d.gotoAndStop(7);
                    trg2.stomps = trg.stomps++;
                  }
                }
                break;
              case 5:
                if (altboss) {
                  f1 = trg.d.d._currentframe;
                  if (f1 > 5 && f1 < 29) {
                    f2 = 50 + 2 * f1;
                    trg2 = parc('bloo', trg.xp + crand(f2), trg.yp + crand(f2));
                    trg2._xscale *= 1 + f1 * 0.05;
                    trg2._yscale = trg2._xscale;
                    colorit(trg2, 0, 0, 0, 255, 255, 255);
                  }
                }
                if (trg.d.d._currentframe == 1) {
                  trg.xp = player.xp;
                  trg.yp = trg.ypp;
                  sizes[101] = 30;
                }
                break;
              case 7:
                if (trg.d.d._currentframe == 1) {
                  trg.xp = player.xp;
                  trg.yp = player.yp;
                  sizes[101] = 15;
                }
            }
            break;
          case 100:
            spidboss = true;
            trg.outway = true;
            trgnextd();
            if (trg.specoz == 20 && fra % 2 == 0 && (trg.d.d._currentframe != 9 or trg.d._currentframe != 7)) {
              trgnextd();
            }
            f1 = 0.8;
            if (f1 != 1) {
              trg.xbew *= f1;
              trg.ybew *= f1;
            }
            trg.bh = true;
            trg.ggh = false;
            switch (trg.d._currentframe) {
              case 5:
                if (trg.d.d._currentframe == 7) {
                  _root.soundy('Boss_Lite_Roar.mp', 100);
                }
                if (trg.d.d._currentframe > 5 && trg.d.d._currentframe < 23) {
                  trg.bh = false;
                  trg.xbew += trg.xpp;
                  trg.ybew += trg.ypp;
                }
                if (trg.d.d._currentframe == 23) {
                  _root.soundy('ForestBoss_Stomps' + random(3) + '.wav', 100);
                  braz();
                }
                trg.xbew *= 0.9;
                trg.ybew *= 0.9;
                break;
              case 1:
                f1 = random(2);
                ++trg.fire;
                enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
                if (random(3) == 0 && enf > 100 or !altboss && ashut > 5 or trg.nextjump) {
                  f1 = 5;
                  trg.nextjump = false;
                  enf = 4 / enf;
                  trg.xbew *= 0.7;
                  trg.ybew *= 0.7;
                  if (trg.specoz == 20) {
                  }
                  trg.xpp = -xenf * enf;
                  trg.ypp = -yenf * enf;
                  trg.runs = 0;
                } else {
                  if (altboss) {
                    f2 = [2, 6];
                    if (ashut < 6) {
                      f2.push(7);
                    }
                  } else {
                    f2 = [2, 6, 7];
                  }
                  f1 = f2[random(f2.length)];
                }
                trg.d.gotoAndStop(f1);
                break;
              case 7:
                if (trg.d.d._currentframe == 3) {
                  _root.soundy('Wheezy_Cough_' + random(3) + '.mp', 160);
                }
                if (trg.d.d._currentframe == 9) {
                  if (altboss) {
                    if (random(3) == 0) {
                      spih();
                    } else {
                      if (random(2) == 0 && ashut < 5) {
                        boil();
                        boil();
                      } else {
                        bigone = true;
                        boil();
                        bigone = undefined;
                      }
                    }
                  } else {
                    if (trg.specoz == 20) {
                      enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
                      enf = -13 / enf;
                      xenf *= enf;
                      yenf *= enf;
                      trg2 = create(trg.xp, trg.yp, 0, xenf + yenf * 0.4, yenf + xenf * 0.4, 0, 18);
                      trg3 = create(trg.xp, trg.yp, 0, xenf - yenf * 0.4, yenf - xenf * 0.4, 0, 18);
                      trg2.fra -= 20;
                      trg2.die = true;
                      trg2.pbh = true;
                      trg3.fra -= 20;
                      trg3.die = true;
                      trg3.pbh = true;
                    } else {
                      if (trg.specoz < 20) {
                        cirf(trg.xp, trg.yp - 15, 8, 6);
                      } else {
                        boil();
                      }
                    }
                  }
                }
                break;
              case 6:
                f1 = trg.d.d._currentframe - 18;
                if (f1 > 0 && f1 < 17 && (altboss or f1 < 8)) {
                  trg2 = parc('bloo', trg.xp + crand(f1 * 3), trg.yp + crand(f1 * 3));
                  trg2._xscale *= 1 + f1 * 0.2;
                  trg2._yscale = trg2._xscale;
                  if (trg.specoz < 20) {
                    colorit(trg2, 0, 0, 0, 0, 0, 0);
                  } else {
                    colorit(trg2, 0, 0, 0, 255, 255, 255);
                  }
                  if (fra % 2 == 0) {
                    _root.soundy('boss2_bubbles' + random(2) + '.wav', 150);
                  }
                }
                if (altboss) {
                  if (trg.d.d._currentframe == 18) {
                    quadf(trg.xp, trg.yp, 10, true);
                  }
                } else {
                  if (boils < 2) {
                    if (trg.d.d._currentframe == 18) {
                      if (trg.specoz == 20) {
                        f1 = 30;
                      } else {
                        if (trg.specoz < 20) {
                          f1 = 94;
                        } else {
                          f1 = 30.3;
                        }
                      }
                      trg.trg2 = create(trg.xp, trg.yp + 30, 0, 0, 0, 0, f1);
                      if (f1 != 94) {
                        ++boils;
                      }
                      trg.nextjump = true;
                      trg.trg2.hp = 10;
                    }
                  }
                  if (trg.d.d._currentframe == 25) {
                    trg.trg2.d.d.hx.gotoAndStop(3);
                    trg.trg2.d.d.hx.d.gotoAndStop(8);
                  }
                }
            }
            break;
          case 99:
            if ((fra + trg.e) % 5 == 0 && fra > 10) {
              f1 = Math.random() * 2;
              f2 = 20 - f1 * 10;
              splater(trg.xp + crand(f2), trg.yp + crand(f1), 1 + random(10), (f1 + 0.4) * trg._xscale / 100);
            }
            if (trgnextd(undefined, true)) {
              if (trg.d._currentframe == 8) {
                if (enfget(trg.xbew, trg.ybew) > 2 && trg.runs++ < 10) {
                  trg.d.d.gotoAndStop(1);
                } else {
                  trg.d.nextFrame();
                }
              } else {
                if (trg.d._currentframe == 7) {
                  trg.d.nextFrame();
                } else {
                  trg.d.gotoAndStop(1);
                }
              }
            }
            f1 = 1;
            if (trg.d._currentframe < 7) {
              f1 = 0.8;
            } else {
              if (fra % 5 == 0) {
                f1 = 0.97;
              }
            }
            if (f1 != 1) {
              trg.xbew *= f1;
              trg.ybew *= f1;
            }
            switch (trg.d._currentframe) {
              case 7:
                if (trg.d.d._currentframe == 3) {
                  _root.soundy('Monster_Roar_1.mp', 100);
                }
                trg.xbew *= 0.8;
                trg.ybew *= 0.8;
                trg.xbew += trg.xpp;
                trg.ybew += trg.ypp;
                break;
              case 1:
                f1 = random(2);
                ++trg.fire;
                if (trg.fire >= 3 or trg.hp < 100) {
                  f1 = 7;
                  trg.fire = 0;
                  enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
                  enf = 4 / enf;
                  trg.xbew *= 0.7;
                  trg.ybew *= 0.7;
                  if (trg.specoz == 7) {
                    enf *= 0.7;
                  }
                  trg.xpp = -xenf * enf;
                  trg.ypp = -yenf * enf;
                  trg.runs = 0;
                } else {
                  f2 = [2, 6];
                  if (ashut < 6) {
                    f2.push(5);
                  }
                  if (trg.specoz == 21) {
                    f2.splice(1, 1);
                  }
                  f1 = f2[random(f2.length)];
                  if (trg.specoz == 7) {
                    f1 = 1;
                  }
                }
                trg.d.gotoAndStop(f1);
                break;
              case 5:
                if (trg.d.d._currentframe == 13) {
                  _root.soundy('summonsound.wav', 110);
                  f1 = 14;
                  if (trg.specoz == 21) {
                    f1 += 0.1;
                  }
                  trg2 = create(trg.xp - 30, trg.yp - 30, 0, 0, -10, 0, f1);
                  trg2.fra = 0;
                  trg2.outway = true;
                }
                break;
              case 6:
                if (trg.d.d._currentframe == 7) {
                  _root.soundy('Boss_Lite_Roar.mp', 100);
                }
                if (trg.d.d._currentframe == 18) {
                  quadf(trg.xp, trg.yp, 10, true);
                  _root.soundy('ForestBoss_Stomps' + random(3) + '.wav', 100);
                }
            }
        }
      }

      function smartsx() {
        bawssmart();
        switch (trg.s) {
          case 94:
          case 85:
            bord();
            f1 = trg.d._currentframe == 5;
            trg.bh = !f1;
            trg.ggh = f1;
            if (f1) {
              trg.xbew = trg.f1;
              trg.ybew = trg.f2;
              trg.df += 0.7;
              trg.d.d._y += trg.df;
              if (trg.d.d._y > -13) {
                trg.d.gotoAndStop(1);
                trg.xp = trg.xpp;
                trg.yp = trg.ypp;
                trg.xpp = undefined;
              }
            } else {
              randrunc();
            }
            break;
          case 96:
            trg2 = trg.trg2;
            if (trg2 == undefined or trg2.dones) {
              trg.s = 18;
              trg.trg2 = undefined;
              trg.mhp = 20;
              trg.hp = 20;
              trg.flyai = true;
              trg.ybb = 0;
              trg.xbb = 0;
              trg.invincible = false;
              attach(trg, 18);
              trg.d._yscale = 118;
              trg.d._xscale = 118;
            } else {
              if (trg2.xp > 10) {
                if (trg2.s == 90 or trg2.shit) {
                  f11 = -(fra * 0.02) * Math.PI + trg.wtf / 2;
                  if (trg.wtf % 2 == 0) {
                    f11 *= -1;
                  }
                  trg.xpp = trg2.xp + Math.sin(f11) * 60;
                  trg.ypp = trg2.yp + Math.cos(f11) * 50;
                } else {
                  if (trg.wtf % 2 == 0) {
                    f11 *= -1;
                  }
                  f11 = fra * 0.04 * Math.PI + trg.wtf / 2;
                  trg.xpp = trg2.xp + Math.sin(f11) * 25;
                  trg.ypp = trg2.yp + Math.cos(f11) * 20;
                }
                trg.invincible = true;
                trg.xp += trg.xpp;
                trg.yp += trg.ypp;
                trg.xp *= 0.5;
                trg.yp *= 0.5;
                trg.xbew *= 0.9;
                trg.ybew *= 0.9;
              }
            }
            break;
          case 74:
          case 75:
          case 76:
            if (trris + 45 + random(100) <= fra && random(100) == 0) {
              trris = fra;
              _root.soundy('boss2_bubbles' + random(2) + '.wav', 100);
            }
          case 77:
            f1 = trg.s - 74;
            f2 = [5, 17, 16, 15];
            f3 = [1, 7, 10, 13];
            f2 = f2[f1];
            f3 = f3[f1];
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            if (fra - trg.fra < 10) {
              trg.d.gotoAndStop(f2);
            }
            if (trg.d._currentframe == f2) {
              trg.xbew *= 0.45;
              trg.ybew *= 0.45;
            }
            trgnextd();
            if (trg.d._currentframe == 1) {
              trg.d.gotoAndStop(f3);
            }
            if (trg.d._currentframe == 13 && trg.d.d._currentframe == 17) {
              if (trriss + 5 + random(20) <= fra) {
                trriss = fra;
                _root.soundy('gooattach0' + random(2) + '.wav', 40 + random(30));
              }
            }
            if (trg.d._currentframe == 10 && trg.d.d._currentframe == 18) {
              _root.soundy('ForestBoss_Stomps' + random(3) + '.wav', 60);
            }
            if ((trg.d._currentframe == 2 or trg.d._currentframe == 7 or trg.d._currentframe == 8) && trg.d.d._currentframe == 22) {
              _root.soundy('ForestBoss_Stomps' + random(3) + '.wav', 80);
            }
            if (trg.d._currentframe == 3 && trg.d.d._currentframe == 24) {
              _root.soundy('ForestBoss_Stomps' + random(3) + '.wav', 100);
            }
            if (trg.d._currentframe == 5 && trg.d.d._currentframe == 22) {
              _root.soundy('ForestBoss_Stomps' + random(3) + '.wav', 120);
            }
            trg.bh = (trg.d._currentframe != 4 or trg.d.d._currentframe < 11) && (trg.d._currentframe != 5 or trg.d.d._currentframe > 21);
            switch (trg.d._currentframe) {
              case 10:
                if (trg.d.d._currentframe == 1) {
                  if (random(2) == 0) {
                    trg.d.gotoAndStop(11);
                  } else {
                    trg.xpp = undefined;
                  }
                } else {
                  randrun();
                }
                if (trg.d.d._currentframe > 19) {
                  trg.xbew *= 0.6;
                  trg.ybew *= 0.6;
                }
                break;
              case 11:
                if (trg.d.d._currentframe == 21) {
                  quadf(trg.xp, trg.yp, 8);
                  _root.soundy('heartout.wav');
                }
                break;
              case 7:
                if (trg.d.d._currentframe == 1) {
                  enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1500);
                  f1 = 0;
                  if (enf < 250) {
                    if (random(2) == 0) {
                      trg.d.gotoAndStop(8);
                      f1 = 0.4;
                    } else {
                      f1 = 1.5;
                    }
                  } else {
                    f1 = 1.5;
                    xenf = crand(10);
                    yenf = crand();
                    enf = 10;
                  }
                  f1 /= enf;
                  trg.xpp = -xenf * f1;
                  trg.ypp = -yenf * f1;
                }
              case 8:
                if (trg.d.d._currentframe < 23 && trg.d.d._currentframe > 4) {
                  if (trg.xpp != undefined) {
                    trg.xbew += trg.xpp;
                    trg.ybew += trg.ypp;
                  }
                } else {
                  trg.xbew *= 0.9;
                  trg.ybew *= 0.9;
                }
                if (trg.d.d._currentframe == 23 && trg.d._currentframe == 8) {
                  quadf(trg.xp, trg.yp, 10, random(2) * 2);
                }
                break;
              case 1:
                if (trg.s == 74) {
                  enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1500);
                  f1 = 0;
                  if (enf < 250) {
                    if (random(2) == 0) {
                      trg.d.gotoAndStop(3);
                      f1 = 0.4;
                    } else {
                      trg.d.gotoAndStop(2);
                      f1 = 1.5;
                    }
                  } else {
                    f1 = 3;
                    trg.d.gotoAndStop(4);
                  }
                  f1 /= enf;
                  trg.xpp = -xenf * f1;
                  trg.ypp = -yenf * f1;
                }
                break;
              case 5:
              case 3:
                if (trg.d.d._currentframe == 23 && fra > 60) {
                  if (trg.d._currentframe == 5) {
                    quadf(trg.xp, trg.yp + 25, 10, true);
                  } else {
                    bossfire(8, false);
                  }
                }
              case 2:
                if (trg.d.d._currentframe < 23 && trg.d.d._currentframe > 4) {
                  if (trg.xpp != undefined) {
                    trg.xbew += trg.xpp;
                    trg.ybew += trg.ypp;
                  }
                } else {
                  trg.xbew *= 0.9;
                  trg.ybew *= 0.9;
                }
                break;
              case 6:
              case 9:
                if (trg.s == 75 && trg.d.d._currentframe == 19 or trg.s == 74 && trg.d.d._currentframe == 30) {
                  if (trg.s == 74) {
                    f1 = 30;
                  } else {
                    f1 = 20;
                  }
                  f1 = crand(f1);
                  f2 = crand();
                  f3 = 0.3;
                  trg2 = create(trg.xp + f1, trg.yp + f2, 0, f1 * f3, f2 * f3, 0, trg.s + 1);
                  trg3 = create(trg.xp - f1, trg.yp - f2, 0, -f1 * f3, -f2 * f3, 0, trg.s + 1);
                  trg2.fra = -100;
                  trg3.fra = -100;
                  trg.dones = true;
                  trg.dfr = true;
                }
                break;
              case 13:
                randrun();
                if (trg.d.d._currentframe == 1) {
                  trg.xpp = undefined;
                }
                if (trg.d.d._currentframe > 19) {
                  trg.xbew *= 0.6;
                  trg.ybew *= 0.6;
                }
            }
            break;
          case 73:
            trg.outway = true;
          case 72:
          case 71:
            if (trg.specoz == 15) {
              trg.xbew *= 0.9;
              trg.ybew *= 0.9;
            }
            f1 = trg.s - 71;
            if (fra - trg.fra < 10) {
              trg.d.gotoAndStop(4 + f1 * 3);
            }
            if (trg.d._currentframe == 4 + f1 * 3) {
              trgnextd();
              trg.xbew *= 0.45;
              trg.ybew *= 0.45;
            }
            if (trg.d._currentframe != 4 + f1 * 3) {
              trg.d.gotoAndStop(2 + f1 * 3);
              f2 = 0.2 + f1 * 0.18;
              if (trg.xbew > 0) {
                xenf = f2;
              } else {
                xenf = -f2;
              }
              if (trg.ybew > 0) {
                yenf = f2;
              } else {
                yenf = -f2;
              }
              trg.xbew *= 0.9;
              trg.ybew *= 0.9;
              trg.xbew += xenf;
              trg.ybew += yenf;
            }
            break;
          case 57:
            if (trg.d._currentframe == 5) {
              if (trg.d.d._currentframe == 26) {
                _root.soundy('ForestBoss_Stomps' + random(3) + '.wav', 80);
              }
            }
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            trgnextd();
            switch (trg.d._currentframe) {
              case 1:
              case 2:
                randrun();
                if (random(30) == 0) {
                  trg.d.gotoAndStop(5);
                }
                break;
              case 5:
                if (trg.d.d._currentframe == 30) {
                  quadf(trg.xp, trg.yp, 10, true);
                }
            }
            sideflip(100);
            break;
          case 43:
          case 20:
            if (altboss && trg.s == 43) {
              blackout = 2;
            }
            trg.bh = (trg.d._currentframe != 6 or trg.d.d._currentframe > 22 or trg.d.d._currentframe < 8) && (trg.d._currentframe != 2 or trg.d.d._currentframe < 8) && (trg.d._currentframe != 3 or trg.d.d._currentframe > 33) && trg.d._currentframe != 5;
            whuf = trg.s == 43 && fra % 2 == 0 && trg.specoz == 14;
            if (trg.weap) {
              trgnextd();
              if (whuf) {
                trgnextd();
              }
              trg.xbew *= 0.8;
              trg.ybew *= 0.8;
              switch (trg.d._currentframe) {
                case 2:
                  if (trg.d.d._currentframe == 16) {
                    trg.done = true;
                  }
                  break;
                case 3:
                  if (!trg.bh) {
                    trg2 = trg.trg2;
                    if (enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, 1000) > 0) {
                      trg.xbew -= xenf * 0.01;
                      trg.ybew -= yenf * 0.01;
                    }
                  }
                  if (trg.d.d._currentframe == 32) {
                    _root.soundy('ForestBoss_Stomps' + random(3) + '.wav', 80);
                    for (z in ball) {
                      trg2 = ball[z];
                      if (trg2.s > 9 && trg != trg2) {
                        if (enfcheck(trg2.xp, trg2.yp, trg.xp, trg.yp, 80)) {
                          hurt(trg2, 120);
                        }
                      }
                    }
                  } else {
                    if (trg.d.d._currentframe == 72) {
                      trg.d.gotoAndStop(2);
                    }
                  }
              }
            } else {
              trg.ggh = !trg.bh;
              trg.flyby = !trg.bh;
              if ((fra + trg.e) % 5 == 0 && fra > 10) {
                splater(trg.xp, trg.yp, 1 + random(10), (Math.random() + 1) * trg._xscale / 100);
              }
              trg.xbew *= 0.9;
              trg.ybew *= 0.9;
              switch (trg.mode) {
                case 10:
                  trg.d.gotoAndStop(7);
                  if (whuf) {
                    trgnextd();
                  }
                  trgnextd();
                  if (trg.d._currentframe == 1) {
                    trg.mode = undefined;
                  }
                  break;
                default:
                  if (trg.fra + 10 > fra) {
                    trg.mode = 10;
                    trg.d.gotoAndStop(7);
                  } else {
                    trg.modedone = false;
                    trg.xpp = undefined;
                    trg.d.gotoAndStop(1);
                    if (trg.s == 43 && !altboss) {
                      yenf = trg.yp - player.yp;
                      if (Math.abs(yenf) < 20 + Math.random() * 50) {
                        trg.mode = 1;
                      } else {
                        if (random(2) == 0) {
                          trg.mode = 2;
                        } else {
                          trg.mode = 0;
                        }
                      }
                    } else {
                      trg.mode = random(3);
                      if (trg.specoz == 2 && trg.mode == 2) {
                        trg.mode = 1;
                      }
                    }
                    if (trg.mode == 2) {
                      _root.soundy('Boss_Lite_Roar.mp', 100);
                    }
                    if (trg.mode == 0) {
                      _root.soundy('Boss_Lite_Roar.mp', 50);
                    }
                    if (trg.mode == 1) {
                      sideflip(trg.xp - player.xp);
                      trg.xpp = trg.xp - player.xp;
                    }
                  }
                  goto 268169;
                case 1:
//Invalid switch              }
              trgnextd();
              if (trg.d._currentframe == 1 && trg.modedone) {
                trg.mode = undefined;
              } else {
                if (altboss && trg.s == 43) {
                  trg.d.gotoAndStop(8);
                  sideflip(trg.xp - player.xp);
                } else {
                  trg.d.gotoAndStop(4);
                }
                if (trg.s == 43) {
                  if (trg.d.d._currentframe > 27 && trg.d.d._currentframe < 60) {
                    if (altboss) {
                      if (trg.d.d._currentframe == 29) {
                        green(true);
                      }
                      trg.modedone = true;
                    } else {
                      trg.ypp = 0;
                      trg.xpp = -trg.d._xscale;
                      lasershow(trg);
                      trg.modedone = true;
                    }
                  }
                } else {
                  if (trg.d.d._currentframe > 23 && !trg.modedone) {
                    _root.soundy('Boss_Spit_Blob_Barf.mp', 100);
                    bossfire(13, true);
                    trg.modedone = true;
                  }
                }
              }
              goto 268169;
            case 98:
              trg.d.gotoAndStop(6);
              trgnextd();
              if (whuf) {
                trgnextd();
              }
              if (trg.xpp == undefined) {
                f1 = player.xp;
                f2 = player.yp;
                f1 = ingrid(f1, f2);
                if (levz[f1] < 1) {
                  outgrid(f1);
                  trg.xpp = xenf;
                  trg.ypp = yenf;
                }
              }
              if (trg.d.d._currentframe == 23) {
                _root.soundy('ForestBoss_Stomps' + random(3) + '.wav', 50);
                if (trg.s == 43) {
                  f1 = trg.xp;
                  f2 = trg.yp;
                  for (a in ball) {
                    trg2 = ball[a];
                    if (trg2.flyai) {
                      if (enfcheck(f1, f2, trg2.xp, trg2.yp, 60)) {
                        hurt(trg2, 30);
                      }
                    }
                  }
                }
              }
              if (trg.xpp != undefined && trg.d._currentframe == 1) {
                if (random(2) == 0) {
                  trg.xpp = undefined;
                  trg.mode = trg.xpp;
                } else {
                  _root.soundy('Boss_Lite_Roar.mp', 40);
                  trg.xpp = undefined;
                }
              } else {
                if (trg.xpp != undefined && trg.d.d._currentframe < 24) {
                  xenf = trg.xp - trg.xpp;
                  yenf = trg.yp - trg.ypp;
                  enf = enfget(xenf, yenf);
                  enf = 1.2 / enf;
                  if (trg.specoz == 14) {
                    enf *= 1.5;
                  }
                  trg.xbew -= xenf * enf;
                  trg.ybew -= yenf * enf;
                  trg.xbew *= 0.9;
                  trg.ybew *= 0.9;
                  sideflip(xenf);
                } else {
                  trg.xbew *= 0.8;
                  trg.ybew *= 0.8;
                }
              }
              goto 268169;
            case 92:
              trg.d.gotoAndStop(2);
              trgnextd();
              if (whuf) {
                trgnextd();
              }
              if (trg.d._currentframe == 1) {
                trg.d.gotoAndStop(3);
                trg.mode = 3;
                trg.modedone = false;
                trg.xpp = undefined;
              } else {}
              goto 268169;
            case 93:
              if (whuf) {
                trgnextd();
              }
              trgnextd();
              if (trg.d._currentframe == 1) {
                bossrep = !bossrep;
                if (!bossrep or trg.s != 43) {
                  trg.mode = undefined;
                  trg.xpp = undefined;
                } else {
                  trg.mode = 2;
                  trg.xpp = undefined;
                }
              }
              if (trg.xpp == undefined) {
                f1 = player.xp;
                f2 = player.yp;
                f1 = ingrid(f1, f2);
                if (levz[f1] < 1) {
                  outgrid(f1);
                  trg.xpp = xenf;
                  trg.ypp = yenf;
                }
              }
              if (trg.d.d._currentframe == 33 or trg.d.d._currentframe == 34 && whuf) {
                f3 = 5;
                if (trg.s == 43) {
                  f1 = trg.xp;
                  f2 = trg.yp;
                  for (a in ball) {
                    trg2 = ball[a];
                    if (trg2.flyai) {
                      if (enfcheck(f1, f2, trg2.xp, trg2.yp, 70)) {
                        hurt(trg2, 30);
                      }
                    }
                  }
                  if (bossrep) {
                    if (altboss) {
                      if (ashut < 3) {
                        trg2 = [];
                        trg2[0] = create(f1, f2, 0, f3, 0, 0, 15);
                        trg2[0].hp -= 20;
                        if (ashut < 2) {
                          trg2[1] = create(f1, f2, 0, -f3, 0, 0, 15);
                          trg2[1].hp -= 20;
                          _root.soundy('summonsound.wav', 150);
                        } else {
                          _root.soundy('summonsound.wav', 100);
                        }
                      }
                    } else {
                      trg2 = [];
                      trg2[0] = create(f1, f2, 0, f3, 0, 0, 61);
                      trg2[2] = create(f1, f2, 0, 0, f3, 0, 61);
                      trg2[0].die = true;
                      trg2[2].die = true;
                      if (trg.specoz != 14) {
                        trg2[1] = create(f1, f2, 0, -f3, 0, 0, 61);
                        trg2[3] = create(f1, f2, 0, 0, -f3, 0, 61);
                        trg2[1].die = true;
                        trg2[3].die = true;
                        _root.soundy('summonsound.wav', 150);
                      } else {
                        _root.soundy('summonsound.wav', 100);
                      }
                    }
                  } else {
                    if (altboss) {
                      trg2 = parc('bloo', trg.xp, trg.yp);
                      trg2._xscale *= 3;
                      trg2._yscale = trg2._xscale;
                      trg2.perm = true;
                      colorit(trg2, 0, 0, 0, 0, 0, 0);
                    } else {
                      quadf(trg.xp, trg.yp, 10, true);
                    }
                  }
                } else {
                  bossfire(18);
                }
                _root.soundy('ForestBoss_Stomps' + random(3) + '.wav', 100);
              }
              if (trg.xpp != undefined && trg.d.d._currentframe < 32) {
                xenf = trg.xp - trg.xpp;
                yenf = trg.yp - trg.ypp;
                enf = enfget(xenf, yenf);
                enf = (0.3 + enf * 0.006) / enf;
                trg.xbew -= xenf * enf;
                trg.ybew -= yenf * enf;
              } else {
                trg.xbew *= 0.8;
                trg.ybew *= 0.8;
              }
            }
            label 268169:
            break;
            label 268169:
          case 97:
          case 55:
            if (trg.d._currentframe < 3) {
              angstfind();
              walkframe(2);
              trg.xbew *= 0.8;
              trg.ybew *= 0.8;
              if (fra % 3 == 0) {
                if (enfcheckx(trg.xp, trg.yp, player.xp, player.yp, 100)) {
                  trg.d.gotoAndStop(5);
                }
              }
            } else {
              trg.xbew *= 0.7;
              trg.ybew *= 0.7;
              trgnextd();
              if (trg.s == 98) {
                if (trg.d.d._currentframe == 19 && trg.d._currentframe == 5) {
                  f1 = true;
                  if (trg.specoz) {
                    f1 = false;
                  }
                  quadf(trg.xp, trg.yp, 8, f1);
                  splater(trg.xp, trg.yp + 12, 1 + random(10), Math.random() + 0.6);
                  splater(trg.xp + crand(10), trg.yp + 12 + crand(10), 1 + random(10), Math.random() * 0.5 + 0.6);
                }
              } else {
                if (trg.d.d._currentframe == 13 && trg.d._currentframe == 5) {
                  quadf(trg.xp, trg.yp, 8);
                }
              }
            }
            break;
          case 31:
            if (!trg.finder) {
              trg.finder = true;
              trg.trg2 = hearts[trg.trg2];
            }
          case 23:
            f2 = false;
            if (trg.trg2.hp <= 0) {
              if (trg.s == 97) {
                if (!altboss) {
                  altboss = true;
                  trg.invincible = false;
                  trg.hp = trg.mhp;
                  trg.d.gotoAndStop(1);
                  f2 = true;
                }
              } else {
                trg.dones = true;
              }
            }
            if (trg.s == 97) {
              if (!altboss) {
                f1 = trg.trg2.hp;
                if (f1 != trg.mhp && f1 < trg.hp) {
                  trg.hp = f1;
                  f2 = true;
                }
              } else {}
              if (f2 && random(2) == 0) {
                chaxy();
                enf = enfcheck(f3, f4, f1, f2, 1000);
                chaxx();
                trg.gogo = 2;
                f1 = 1.6;
                trg.xpp *= f1;
                trg.ypp *= f1;
              }
            }
            trg.ggh = fra % 2 == 0;
            markhere(trg);
            if (Math.abs(trg.xbeww) > Math.abs(trg.ybeww)) {
              if (trg.xbeww > 0) {
                f1 = 7;
              } else {
                f1 = 6;
              }
            } else {
              if (trg.ybeww > 0) {
                f1 = 1;
              } else {
                f1 = 5;
              }
            }
            trg.xbeww += trg.xbew;
            trg.ybeww += trg.ybew;
            trg.xbeww *= 0.35;
            trg.ybeww *= 0.35;
            if (trg.xpp != undefined) {
              trg.d.gotoAndStop(f1);
            }
            if (!trg.gogo or trg.gogo == 2) {
              if ((fra + trg.e) % 4 == 0) {
                if (chaa()) {
                  if (trris2 + 20 <= fra && trg.s != 93 && trg.s != 97) {
                    trris2 = fra;
                    _root.soundy('maggotcharge' + random(2) + '.wav');
                  }
                  trg.xpp *= 2;
                  trg.ypp *= 2;
                  trg.gogo = true;
                }
              }
            }
            if (!trg.gogo) {
              if (altboss && trg.s == 97) {
                randrunx(1.5);
              } else {
                randrunx(0.85);
              }
              trg.xbew *= 0.85;
              trg.ybew *= 0.78;
            } else {
              if (trg.gh) {
                trg.gogo = false;
                trg.ypp = undefined;
                trg.xpp = trg.ypp;
              } else {
                trg.xbew *= 0.82;
                trg.ybew *= 0.82;
                trg.xbew += trg.xpp;
                trg.ybew += trg.ypp;
                trg.xbeww += trg.xpp * 3;
                trg.ybeww += trg.ypp * 3;
                outgrid(trg.til);
                if (Math.abs(trg.xbew) > Math.abs(trg.ybew)) {
                  trg.yp *= 0.9;
                  trg.yp += yenf * 0.1;
                } else {
                  trg.xp *= 0.9;
                  trg.xp += xenf * 0.1;
                }
                trg.d.gotoAndStop(f1);
              }
            }
            break;
          case 21:
          case 34:
          case 54:
          case 29:
            trg.ggh = fra % 2 == 0;
            trg.gonuts = trg.s == 23 or trg.s == 55;
            markhere(trg);
            if (trg.fire-- > 0) {
              trg.xbew *= 0.85;
              trg.ybew *= 0.85;
              trg.d.d.nextFrame();
              if (trg.d.d._currentframe == trg.d.d._totalframes) {
                trg.fire = 0;
              }
              if (trg.d.d._currentframe == 8) {
                f1 = 8;
                if (Math.abs(trg.xpp) > Math.abs(trg.ypp)) {
                  trg.ypp = 0;
                  if (trg.xpp > 0) {
                    trg.xpp = f1;
                  } else {
                    trg.xpp = -f1;
                  }
                } else {
                  trg.xpp = 0;
                  if (trg.ypp > 0) {
                    trg.ypp = f1;
                  } else {
                    trg.ypp = -f1;
                  }
                }
                trg2 = create(trg.xp, trg.yp, 0, trg.xpp, trg.ypp, 0, 9, trg.s);
                trg2.dy = -14;
                trg2.fd = -0.08;
                trg.xpp = undefined;
              }
            } else {
              if (!trg.gogo) {
                if (trg.s == 21) {
                  randrunx(0.75);
                } else {
                  if (trg.s == 55) {
                    randrunx(0.85);
                  } else {
                    if (trg.s == 31) {
                      randrunx(0.72);
                    } else {
                      randrunx(0.6);
                    }
                  }
                }
                trg.xbew *= 0.85;
                trg.ybew *= 0.7;
                if (Math.abs(trg.xbew) > Math.abs(trg.ybew)) {
                  f1 = 1;
                  sideflip(-trg.xbew);
                } else {
                  if (trg.ybew > 0) {
                    f1 = 2;
                  } else {
                    f1 = 5;
                  }
                }
                trg.d.gotoAndStop(f1);
                if (trg.gonuts && (fra + trg.e) % 4 == 0) {
                  trg.gogo = chaa(trg.s == 55);
                  if (trg.gogo) {
                    if (trg.s == 55) {
                      if (trris + 20 <= fra) {
                        trris = fra;
                        _root.soundy('leech' + random(3) + '.wav');
                      }
                      trg.xpp *= 1.55;
                      trg.ypp *= 1.55;
                    } else {
                      if (trris2 + 20 <= fra) {
                        trris2 = fra;
                        _root.soundy('maggotcharge' + random(2) + '.wav');
                      }
                      trg.xpp *= 1.3;
                      trg.ypp *= 1.3;
                    }
                  }
                } else {
                  if (random(35) == 0 && trg.s == 31) {
                    trg.d.gotoAndStop(trg.d._currentframe + 5);
                    trg.xpp = trg.xbew;
                    trg.ypp = trg.ybew;
                    trg.fire = 50;
                  }
                }
              } else {
                if (trg.gh) {
                  trg.gogo = false;
                  trg.ypp = undefined;
                  trg.xpp = trg.ypp;
                } else {
                  if (trg.s == 23) {
                    trg.xbew *= 0.8;
                    trg.ybew *= 0.8;
                  } else {
                    trg.xbew *= 0.9;
                    trg.ybew *= 0.9;
                  }
                  trg.xbew += trg.xpp;
                  trg.ybew += trg.ypp;
                  outgrid(trg.til);
                  if (Math.abs(trg.xbew) > Math.abs(trg.ybew)) {
                    f1 = 7;
                    sideflip(-trg.xbew);
                    trg.yp *= 0.9;
                    trg.yp += yenf * 0.1;
                  } else {
                    if (trg.ybew > 0) {
                      f1 = 6;
                    } else {
                      f1 = 8;
                    }
                    trg.xp *= 0.9;
                    trg.xp += xenf * 0.1;
                  }
                  if (trg.s == 55) {
                    if (Math.abs(trg.xbew) > Math.abs(trg.ybew)) {
                      f1 = 1;
                    } else {
                      if (trg.ybew > 0) {
                        f1 = 2;
                      } else {
                        f1 = 5;
                      }
                    }
                  }
                  trg.d.gotoAndStop(f1);
                }
              }
            }
            tip(0);
            break;
          case 86:
            if (random(7) == 0) {
              splater(trg.xp, trg.yp, trg.spl + 1 + random(10), Math.random() * 0.12);
            }
          case 28:
          case 10:
          case 1:
            if (trg.flyby) {
              if (trg.d._currentframe < 5) {
                trgnextd();
                trg.d.gotoAndStop(5);
                trg.xpp = player.xp;
                trg.ypp = player.yp;
                trg.f1 = 0;
              } else {
                trg.xbew *= 0.8;
                trg.ybew *= 0.8;
                if (trg.d._currentframe == 5 && trg.d.d._currentframe > 6 or trg.d._currentframe == 6 && trg.d.d._currentframe < 18) {
                  trg.f1 += 0.02;
                  trg.xp = trg.xpp * trg.f1 + trg.xp * (1 - trg.f1);
                  trg.yp = trg.ypp * trg.f1 + trg.yp * (1 - trg.f1);
                  trg.bh = false;
                } else {
                  trg.bh = true;
                }
                if (trg.d._currentframe == 5) {
                  trgnextd();
                  if (trg.d._currentframe == 1) {
                    trg.d.gotoAndStop(6);
                  }
                } else {
                  trgnextd();
                  if (trg.d.d._currentframe == 19) {
                    _root.soundy('Meat_impacts_' + random(3) + '.wav', 200);
                    quadf(trg.xp, trg.yp, 9);
                  }
                  if (trg.d._currentframe == 1) {
                    trg.flyby = false;
                    trg.xpp = undefined;
                  }
                }
              }
            } else {
              randruny();
              trg.xbew *= 0.7;
              trg.ybew *= 0.7;
              if (trg.s == 34) {
                if (trg.xpp == undefined && random(7) == 0) {
                  trg.flyby = true;
                }
              }
            }
            break;
          case 0:
            if (altboss && altboss != 2) {
              f1 = trg.hp / hps[trg.s];
              trg._yscale = 70 + f1 * 35;
              trg._xscale = trg._yscale;
              trg.xbew *= 1.1 - f1 * 0.14;
            }
            ++magget;
            trg.mag = magget;
            mags[magget] = trg;
            if (!firstmag) {
              firstmag = true;
            } else {
              if (magget >= 4) {
                trg.mag -= 3;
                trg.mags = [0, mags[4], mags[5], mags[6]];
              } else {
                trg.mags = [0, mags[1], mags[2], mags[3]];
              }
              if (fra - 20 < trg.fra) {
                trg.d.gotoAndStop(trg.mag + 9);
              }
              if (altboss == 2) {
                if (trg.mag < 3) {
                  trg.invincible = true;
                }
              }
              if (trg.d._currentframe >= 10) {
                trgnextd();
                trg.xbew = 0;
                trg.ybew = 0;
                if (trg.mag == 3 && !trg.wtfu) {
                  trg.wtfu = true;
                  trg.xp *= 0.65;
                  trg.yp *= 0.65;
                  trg.xp += trg.mags[2].xp * 0.35;
                  trg.yp += trg.mags[2].yp * 0.35;
                }
              }
              if (trg.d._currentframe < 10) {
                trg.d.gotoAndStop(trg.mag);
                markhere(trg);
                if (trg.mag != 1) {
                  trg2 = trg.mags[trg.mag - 1];
                  if (trg2.beenx.length > 0) {
                    f10 = true;
                    while (f10) {
                      if (trg.specoz == 9) {
                        f0 = Math.min(15 - trg.mag * 2, trg2.beenx.length - 1);
                      } else {
                        if (trg.specoz > 18) {
                          f0 = Math.min(16 - trg.mag * 2, trg2.beenx.length - 1);
                        } else {
                          f0 = Math.min(17 - trg.mag * 2, trg2.beenx.length - 1);
                        }
                      }
                      enf = enfcheck(trg.xp, trg.yp, trg2.beenx[f0], trg2.beeny[f0], 1000);
                      f2 = 10;
                      if (enf < f2) {
                        trg.xp = trg2.beenx[f0];
                        trg.yp = trg2.beeny[f0];
                        f10 = false;
                      } else {
                        enf = f2 / enf;
                        xenf *= enf;
                        yenf *= enf;
                        trg.xp -= xenf;
                        trg.yp -= yenf;
                        trg2.beenx.push(trg2.beenx[f0] + xenf);
                        trg2.beeny.push(trg2.beeny[f0] + yenf);
                      }
                    }
                  }
                } else {
                  trg.d.gotoAndStop(1);
                  killshit(trg.nextl);
                  switch (trg.mode) {
                      if (altboss == 2 && trg.hp / trg.mhp < 0.3 && !trg.specoz) {
                        if (trg.xbew > 0) {
                          xenf = 1;
                        } else {
                          xenf = -1;
                        }
                        if (trg.ybew >= 0.1) {
                          yenf = 1;
                        } else {
                          yenf = -1;
                        }
                        trg.xbew += xenf * 2;
                        trg.ybew += yenf * 2;
                      } else {
                        randrunx(1.5);
                        if (trg.charf + 50 <= fra) {
                          if (chaa()) {
                            trg.charf = fra;
                            trg.mode = 2;
                            _root.soundy('Monster_Roar_0.mp', 100);
                          }
                        }
                        f1 = altboss == 2 && !trg.specoz;
                        if (trg.mode != 2 && random(100) == 0 && (ashut < 5 && !f1 or f1 && chubber < 5 && fra >= lastpoop) && (trg.specoz != 8 or ashut < 4 or random(4) == 0)) {
                          _root.soundy('Monster_Roar_1.mp', 100);
                          lastpoop = fra + 100;
                          trg.mode = 3;
                          magss = fra + 10;
                        }
                      }
                      f2 = 0;
                    case 4:
                      f2 = 12;
                      ++trg.bomb;
                      if (trg.bomb == 3) {
                      }
                      if (trg.bomb > 35) {
                        trg.bomb = undefined;
                        trg.mode = 0;
                        trg.d.d.gotoAndStop(1);
                        hurt(trg, 20);
                        bombfail(trg.xp, trg.yp, 5);
                        trg.xpp = undefined;
                        f2 = 0;
                        _root.soundy('Monster_Roar_2.mp', 50);
                      }
                      break;
                    case 2:
                      if (trg.gh) {
                        trg.mode = 1;
                        trg.ypp = undefined;
                        trg.xpp = trg.ypp;
                      } else {
                        trg.xbew *= 0.9;
                        trg.ybew *= 0.9;
                        trg.xbew += trg.xpp * 3.7;
                        trg.ybew += trg.ypp * 3.7;
                      }
                      f2 = 6;
                      break;
                    case 3:
                      f1 = fra - magss;
                      if (f1 > 0) {
                        f2 = 9;
                      } else {
                        f2 = 3;
                      }
                      if (f1 > 20) {
                        trg.mode = 1;
                      }
                  }
                  if (Math.abs(trg.xbew) > Math.abs(trg.ybew)) {
                    sideflip(-trg.xbew);
                    f1 = 2;
                  } else {
                    if (trg.ybew > 0) {
                      f1 = 1;
                    } else {
                      f1 = 3;
                    }
                  }
                  if (trg.d.d._currentframe <= 12) {
                    trg.d.d.gotoAndStop(f1 + f2);
                  }
                }
                enf = enfcheck(trg.xp, trg.yp, trg.beenx[0], trg.beeny[0], 1000);
                while (enf > 2) {
                  enf = 2 / enf;
                  trg.beenx.unshift(trg.beenx[0] + xenf * enf);
                  trg.beeny.unshift(trg.beeny[0] + yenf * enf);
                  enf = enfcheck(trg.xp, trg.yp, trg.beenx[0], trg.beeny[0], 1000);
                }
                if (trg.beenx.length > 30) {
                  f2 = [];
                  f3 = [];
                  a = 0;
                  while (a < 20) {
                    f2[a] = trg.beenx[a];
                    f3[a] = trg.beeny[a];
                    ++a;
                  }
                  trg.beenx = new Array(20);
                  trg.beeny = new Array(20);
                  a = 0;
                  while (a < 20) {
                    trg.beenx[a] = f2[a];
                    trg.beeny[a] = f3[a];
                    ++a;
                  }
                }
                if (trg.specoz == 8) {
                  trg.xbew *= 0.75;
                  trg.ybew *= 0.75;
                } else {
                  if (trg.specoz == 9) {
                    trg.xbew *= 0.86;
                    trg.ybew *= 0.86;
                  } else {
                    trg.xbew *= 0.8;
                    trg.ybew *= 0.8;
                  }
                }
                if (trg.mag == 3 && trg.specoz == 22) {
                  for (i in hearts) {
                    trg2 = hearts[i];
                    if (trg2.hp <= -10 or trg2.dones) {
                      _root.soundy('Monster_Roar_2.mp', 50);
                      hurt(trg, 40);
                      hearts.splice(i, 1);
                    }
                  }
                }
                if (fra > 20 && magss == fra && trg.mag == 3) {
                  f1 = 5;
                  f2 = ingrid(trg.beenx[f1], trg.beeny[f1]);
                  outgrid(f2);
                  if (altboss == 2) {
                    if (trg.specoz) {
                      if (ashut < 5) {
                        trg2 = create(xenf, yenf, 0, 0, 0, 0, 92);
                        trg2._yscale = 50;
                        trg2._xscale = 50;
                        trg2.hp *= 0.7;
                      } else {
                        f1 = -1;
                      }
                    } else {
                      turd('breakblock2', f2, true);
                      ++chubber;
                    }
                  } else {
                    if (altboss) {
                      f1 = 61;
                    } else {
                      if (trg.specoz == 8) {
                        f1 = 30;
                      } else {
                        if (trg.specoz == 9) {
                          f1 = 31;
                        } else {
                          f1 = 23;
                        }
                      }
                    }
                    if (f1 != 30) {
                      create(xenf, yenf, 0, 0, 0, 0, f1);
                      _root.soundy('summonsound.wav', 100);
                    } else {
                      _root.soundy('summonsound.wav', 70);
                    }
                    trg2 = create(xenf, yenf, 0, 0, 0, 0, f1);
                  }
                  if (f1 > 0) {
                    if (f1 == 30) {
                      trg2.spl = 30;
                      trg2.specoz = 10;
                      trg2.outway = true;
                      specialColoring(trg2);
                    }
                    xenf -= trg.xp;
                    yenf -= trg.yp;
                    trg2.xbew += xenf * 0.1;
                    trg2.ybew += yenf * 0.1;
                    trg2.d.d.gotoAndStop(1);
                    f1 = 0;
                    if (enfget(trg.xbew, trg.ybew) > 2) {
                      if (Math.abs(xenf) > Math.abs(yenf)) {
                        sideflip(xenf);
                        f1 = 2;
                      } else {
                        if (yenf > 0) {
                          f1 = 3;
                        } else {
                          f1 = 4;
                        }
                      }
                      trg.d.d.gotoAndStop(f1);
                    }
                  }
                }
              }
            }
//Invalid switch        }
      }

      function ssmarts() {
        switch (trg.s) {
          case 45:
            if (trg.d._currentframe == 5) {
              if (trg.d.d._currentframe == 5) {
                _root.soundy('ForestBoss_Stomps' + random(3) + '.wav', 150);
              }
            }
            if (trg.specoz == 19) {
              if (trg.d._currentframe == 5) {
                if (trg.d.d._currentframe == 20) {
                  trg.d.d.gotoAndStop(38);
                }
              }
              if (trg.d._currentframe == 2) {
                if (trg.d.d._currentframe == 3 && fra > 60) {
                  enf = enfcheck(trg.xp, trg.yp, player.xp, player.yp, 10000);
                  enf = -10 / enf;
                  xenf *= enf;
                  yenf *= enf;
                  shots(trg.xp + xenf, trg.yp + yenf, xenf, yenf, true);
                }
              }
              if (trg.d._currentframe == 20) {
                if (trg.d.d._currentframe == 48) {
                  trg.d.d.gotoAndStop(58);
                }
                if (trg.d.d._currentframe < 20 or trg.d.d._currentframe > 65) {
                  trg.d.d.nextFrame();
                }
              }
            }
            trg.bh = trg.d._currentframe == 20 && trg.d.d._currentframe > 27 && trg.d.d._currentframe < 62 or trg.d._currentframe == 19;
            if (trg.d._currentframe == 20 && trg.d.d._currentframe == 26 or trg.whu == 3) {
              trg.whu = 0;
              trg.dmg = 300;
              gosplash();
              _root.soundy('Hellboss_Groundpound_' + random(2) + '.wav');
            }
            if (trg.weap) {
              if (trg.d._currentframe == 20) {
                if (trg.d.d._currentframe < 24) {
                  trg2 = trg.trg2;
                  if (enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, 1000) > 0) {
                    trg.xbew -= xenf * 0.03;
                    trg.ybew -= yenf * 0.03;
                  }
                }
                if (trg.d.d._currentframe == 74) {
                  trg.done = true;
                }
              }
              trg.xbew *= 0.8;
              trg.ybew *= 0.8;
            } else {
              mom[momet] = trg;
              ++momet;
              trg.mom = momet;
              if (trg.xpp > 0) {
                trg.xp = trg.xpp;
                trg.yp = trg.ypp;
                trg.xbew *= 0.8;
                trg.ybew *= 0.8;
              }
              if (fra < 20) {
                if (trg.mom == mome) {
                  trg.d.gotoAndStop(2);
                } else {
                  trg.d.gotoAndStop(1);
                }
                if (mome == undefined && trg.mom == 5) {
                  momlo();
                }
                oldm = 3;
              }
              if (trg.d._currentframe != 19) {
                trgnextd();
              }
              if (trg.mom == 3) {
                if (moml - fra < 0) {
                  f1 = random(3);
                  if (fra < 50) {
                    f1 = 0;
                  }
                  mome = -1;
                  if (trg.specoz == 19) {
                    f1 = 0;
                    if (random(4) == 0 && oldm != 2) {
                      f1 = 2;
                    }
                    oldm = -1;
                  }
                  if (oldm != f1) {
                    switch (f1) {
                      case 0:
                        _root.soundy('Mom_Vox_Grunt_' + random(4) + '.mp');
                        moml = fra + 80;
                        if (trg.specoz == 19) {
                          moml -= 30;
                        }
                        for (i in mom) {
                          if (i != 2) {
                            trg2 = mom[i];
                            if (enfcheckx(trg2.xp, trg2.yp, player.xp, player.yp, 100) or enfcheck(trg2.xp, trg2.yp, player.xp, player.yp, 75)) {
                              mome = i;
                            }
                          }
                        }
                        if (mome > -1 && fra > 50) {
                          mom[mome].d.gotoAndStop(5);
                        } else {
                          trg.d.gotoAndStop(20);
                          trg.d.d.gotoAndStop(1);
                          trg._visible = true;
                          if (fra < 50) {
                            trg.xpp = trg.xp;
                            trg.ypp = trg.yp;
                          } else {
                            trg.xpp = player.xp;
                            trg.ypp = player.yp;
                          }
                        }
                        break;
                      case 1:
                        if (ashut < 8) {
                          moml = fra + 45;
                          z = 0;
                          for (;;) {
                            if (!(z < random(3) + 2 && ashut < 8 + random(2))) break;
                            i = random(5);
                            if (i != 2) {
                              ++z;
                              ++ashut;
                              mom[i].d.gotoAndStop(random(2) + 3);
                            }
                            undefined;
                          }
                        }
                        break;
                      case 2:
                        momlo();
                    }
                    oldm = f1;
                  }
                }
                if (trg.d._currentframe < 20) {
                  trg._visible = false;
                }
              } else {
                if (trg.d._currentframe == 3 or trg.d._currentframe == 4) {
                  if (trg.d.d._currentframe == 3) {
                    if (trg.specoz) {
                      f1 = [85, 94, 89, 86, 29.1];
                    } else {
                      f1 = [10, 11, 12, 14, 15, 16, 18, 21, 23, 24, 25.5, 26];
                    }
                    xenf = trg.xp - 320;
                    yenf = trg.yp - 280;
                    enf = enfget(xenf, yenf);
                    enf = 18 / enf;
                    xenf *= enf;
                    yenf *= enf;
                    f2 = random(f1.length);
                    create(trg.xp - xenf, trg.yp - yenf, 0, -xenf, -yenf, 0, f1[f2]);
                    _root.soundy('summonsound.wav', f2 * 5 + 80);
                  }
                }
                if (trg.d._currentframe == 5) {
                  trg2 = mom[2];
                  if (trg.d.d._currentframe > 45) {
                    trg2.d.gotoAndStop(18);
                  } else {
                    if (trg.d.d._currentframe > 3) {
                      trg2.whu = trg.d.d._currentframe;
                      trg2.d.gotoAndStop(19);
                      xenf = trg.xp - 320;
                      yenf = trg.yp - 280;
                      enf = enfget(xenf, yenf);
                      enf = 60 / enf;
                      trg2.xpp = trg.xp - xenf * enf;
                      trg2.xp = trg2.xpp;
                      trg2.ypp = trg.yp - yenf * enf;
                      trg2.yp = trg2.ypp;
                    }
                  }
                }
                trg.bh = trg.d._currentframe != 1;
                if (trg.xpp <= 0) {
                  for (a in door) {
                    trg2 = door[a];
                    if (enfcheck(trg2._x, trg2._y, trg.xp, trg.yp, 50)) {
                      trg.xpp = trg2._x;
                      trg.ypp = trg2._y;
                      trg.d._rotation = trg2._rotation + 90;
                      trg2._visible = false;
                    }
                  }
                }
              }
            }
            break;
          case 33:
            trg.d.nextFrame();
            if (trg.holi) {
            }
            dang2 = trg;
            break;
          case 41:
            sideflip(trg.xbew, trg.d.d);
            if (Math.abs(trg.xbew) > Math.abs(trg.ybew)) {
              if (trg.xbew > 0) {
                f1 = 2;
              } else {
                f1 = 4;
              }
              trg.d.d.gotoAndStop(2);
            } else {
              if (trg.ybew > 0) {
                f1 = 1;
              } else {
                f1 = 3;
              }
              trg.d.d.gotoAndStop(1);
            }
            trg.d.hx.h.gotoAndStop(f1);
          case 44:
            if (trg.s == 44 && ashut == 0 && fra > 80 && trg.alter != 2) {
              trg.dones = true;
            }
            markhere(trg);
            if (!trg.gogo) {
              f2 = true;
              if (trg.s == 44) {
                if (trg.alter == 1) {
                  randrunx(1);
                } else {
                  enf = enfcheck(trg.xp, trg.yp, trg.xppp, trg.yppp, 1000);
                  f1 = Math.min(enf / 10, 1.8);
                  f2 = f1 < 0.4;
                  f1 /= enf;
                  trg.xbew -= xenf * f1;
                  trg.ybew -= yenf * f1;
                }
              } else {
                randrunx(0.75 + trg.alter * 0.25);
              }
              trg.xbew *= 0.8;
              trg.ybew *= 0.8;
              if ((fra + trg.e) % 3 == 0 && f2) {
                trg.gogo = chaa();
                if (trg.alter == 2 && trg.gogo) {
                  trg.xpp *= 1.65;
                  trg.ypp *= 1.65;
                }
                if (trg.alter == 2 && trg.s == 44 && trg.gogo) {
                  trg.xpp *= 1.65;
                  trg.ypp *= 1.65;
                }
              }
            }
            if (trg.gogo) {
              if (trg.gh) {
                trg.gogo = false;
                trg.ypp = undefined;
                trg.xpp = trg.ypp;
              } else {
                trg.xbew *= 0.8;
                trg.ybew *= 0.8;
                trg.xbew += trg.xpp;
                trg.ybew += trg.ypp;
                outgrid(trg.til);
                if (trg.s == 44) {
                  f1 = 5;
                  if (Math.abs(trg.xpp) > Math.abs(trg.ypp)) {
                    trg.yp *= 0.5;
                    trg.yp += yenf * 0.5;
                    if (trg.s == 44) {
                      trg.ybew *= 0.5;
                    }
                  } else {
                    trg.xp *= 0.5;
                    trg.xp += xenf * 0.5;
                    if (trg.s == 44) {
                      trg.xbew *= 0.5;
                    }
                  }
                } else {
                  if (Math.abs(trg.xbew) > Math.abs(trg.ybew)) {
                    trg.yp *= 0.9;
                    trg.yp += yenf * 0.1;
                  } else {
                    trg.xp *= 0.9;
                    trg.xp += xenf * 0.1;
                  }
                }
              }
            }
            break;
          case 40:
            borderliner(3);
            trg.d.d._rotation += enfget(trg.xbew, trg.ybew) * 4;
            trg.d.sh.d._rotation = trg.d.d._rotation;
            if ((fra + trg.e) % 5 == 0) {
              splater(trg.xp, trg.yp + 5, 1 + random(10), Math.random() * 0.7);
            }
            break;
          case 47:
            if (trg.alter == 2) {
              trg.xbew *= 0.95;
              trg.ybew *= 0.95;
              if (fra % 7 == 0) {
                trg2 = parc('bloo', trg.xp, trg.yp, 0, 123);
              }
            } else {
              trg.xbew *= 0.95;
              trg.ybew *= 0.95;
            }
            sideflip(trg.xbew);
            walkframe();
            if (Math.abs(trg.xbew) < Math.abs(trg.ybew)) {
              trg.d.bo.gotoAndStop(2);
            } else {
              trg.d.bo.gotoAndStop(3);
            }
            if (enfcheck(trg.xp, trg.yp, player.xp + player.xbew * 5, player.yp + player.ybew * 5, 1000)) {
              if (linecheck(trg.xp, trg.yp, player.xp, player.yp)) {
                enf = 0.65 / enf;
                trg.xbew -= xenf * enf;
                trg.ybew -= yenf * enf;
                trg.gridimer = -3;
                trg.tiletimer = -3;
              } else {
                pathfind(trg, playx, playy, 1.2);
              }
            }
            break;
          case 46:
            trg.xbew *= 0.75;
            trg.ybew *= 0.75;
            walkframe();
            trgnextd();
            if (trg.d._currentframe < 3) {
              sideflip(trg.xbew);
              randrunx(1);
              if (random(50) == 0) {
                if (random(2) == 0 && ashut < 4 or Math.abs(trg.yp - player.yp) > 60 && trg.minb == 3) {
                  trg.d.gotoAndStop(6);
                } else {
                  trg.d.gotoAndStop(5);
                }
              }
            } else {
              sideflip(player.xp - trg.xp);
              if (trg.alter == 3) {
                if (trg.d.d._currentframe > 5 && trg.d.d._currentframe < 15 && trg.d._currentframe != 6) {
                  z = trg.d.d._currentframe - 5;
                  trg2 = parc('bloo', trg.xp + trg.d._xscale * z / 4, trg.yp);
                  trg2._xscale *= 1.6 + z * 0.07000000000000001;
                  trg2._yscale = trg2._xscale;
                  colorit(trg2, 0, 2, 0, 0, 40, 0);
                }
              }
              if (trg.d.d._currentframe == 5) {
                if (trg.d._currentframe == 6) {
                  if (trg.alter == 3) {
                    bossfire(3, true, 10);
                    _root.soundy('heartout.wav', 70);
                  } else {
                    if (trg.alter == 2) {
                      boil(true);
                      boil(true);
                    } else {
                      trg2 = create(trg.xp + trg.d._xscale * 0.3, trg.yp, 0, 0, 0, 0, 23);
                      _root.soundy('summonsound.wav', 80);
                      _root.soundy('Monster_Grunt_2_' + abr() + '.mp', 100);
                      trg2.apf = true;
                      trg2.gogo = true;
                      trg2.xpp = trg.d._xscale / 100;
                      trg2.ypp = 0;
                      trg.outway = true;
                    }
                  }
                } else {
                  if (trg.alter == 3) {
                  } else {
                    green();
                    if (trg.alter == 2) {
                      green();
                    }
                  }
                  _root.soundy('heartout.wav', 70);
                }
              }
            }
            break;
          case 53:
            trg.alt = Math.abs(player.xp - 320) > Math.abs(player.yp - 280) * 0.65;
            trg.xbew *= 0.75;
            trg.ybew *= 0.75;
            if (trg.alter == 2) {
              trg.flyby = true;
            }
            if (enfget(trg.xbew, trg.ybew) > 2) {
              if (Math.abs(trg.xbew) < Math.abs(trg.ybew)) {
                if (trg.alter == 2) {
                  trg.d.hx.bo.gotoAndStop(1);
                } else {
                  trg.d.hx.bo.gotoAndStop(2);
                }
              } else {
                if (trg.alter == 2) {
                  trg.d.hx.bo.gotoAndStop(2);
                } else {
                  trg.d.hx.bo.gotoAndStop(3);
                }
              }
            } else {
              trg.d.hx.bo.gotoAndStop(1);
            }
            f1 = plo;
            f2 = f1 == 3 or f1 == 1;
            if (!trg.alt && f2 or trg.alt && !f2) {
              f1 += 2;
              if (f1 > 4) {
                f1 -= 4;
              }
            }
            --trg.fire;
            if (player.fire > lpf) {
              if (trg.fire <= 0) {
                f3 = 10;
                yenf = 0;
                xenf = 0;
                switch (f1) {
                  case 1:
                    xenf = 0;
                    yenf = f3;
                    break;
                  case 3:
                    xenf = 0;
                    yenf = -f3;
                    break;
                  case 2:
                    xenf = f3;
                    yenf = 0;
                    break;
                  case 4:
                    xenf = -f3;
                    yenf = 0;
                }
                if (trg.alter == 2) {
                  trg.fire = 30;
                  shots(trg.xp, trg.yp, xenf, yenf, true);
                } else {
                  shots(trg.xp, trg.yp, xenf, yenf);
                }
              }
            }
            lpf = player.fire;
            if (plox > 8) {
              f1 += 4;
            }
            trg.d.hx.h.gotoAndStop(f1);
            if (trg.d.hx.bo != undefined) {
              sideflip(trg.xbew, trg.d.hx.bo);
            }
            trgnextd();
            trg.xpp = trg.xp;
            trg.ypp = trg.yp;
            trg.xp = 640 - player.xp;
            trg.yp = 580 - player.yp;
            trg.xbew = -player.xbew;
            trg.ybew = -player.ybew;
            break;
          case 51:
            f1 = 0.25 + trg.tier * 0.1;
            if (tier == 3) {
              f1 = 0.35;
            }
            if (trg.ybew > 0) {
              f2 = f1;
            } else {
              f2 = -f1;
            }
            if (trg.xbew > 0) {
              f1 = f1;
            } else {
              f1 = -f1;
            }
            trg.xbew *= 0.9;
            trg.ybew *= 0.9;
            trg.xbew += f1;
            trg.ybew += f2;
            sideflip(trg.xbew);
            break;
          case 52:
            trg.xbew *= 0.75;
            trg.ybew *= 0.75;
            if (enfget(trg.xbew, trg.ybew) < 1) {
              trg.d.bo.gotoAndStop(1);
            } else {
              if (Math.abs(trg.xbew) < Math.abs(trg.ybew)) {
                trg.d.bo.gotoAndStop(2);
              } else {
                trg.d.bo.gotoAndStop(3);
              }
            }
            sideflip(-trg.xbew);
            trgnextd();
            if (trg.d._currentframe < 3) {
              randrunx(1);
              if (random(50) == 0) {
                if (random(2) == 0) {
                  trg.d.gotoAndStop(6);
                } else {
                  trg.d.gotoAndStop(5);
                }
              }
            } else {
              if (trg.d._currentframe == 5) {
                if (trg.d.d._currentframe >= 20 && trg.d.d._currentframe <= 37) {
                  lasershowx((0.25 + 0.5 * (fra % 4)) * Math.PI);
                }
                if (trg.alter == 2 && trg.d.d._currentframe == 20) {
                  cirf(trg.xp, trg.yp - 20, 8, 6);
                }
              }
              if (trg.d.d._currentframe == 5) {
                if (trg.d._currentframe == 6) {
                  anarch = 20;
                  if (trg.alter == 2) {
                    anarch = 10;
                    analt = 5;
                  }
                }
              }
            }
            break;
          case 50:
            trg.f3 = 1;
            trg.xbew *= 0.75;
            trg.ybew *= 0.75;
            walkframe();
            if (Math.abs(trg.xbew) < Math.abs(trg.ybew)) {
              trg.d.bo.gotoAndStop(1);
            } else {
              trg.d.bo.gotoAndStop(2);
            }
            sideflip(-trg.xbew);
            trgnextd();
            if (trg.d._currentframe < 3) {
              randrunx(1);
              if (random(50) == 0) {
                if (random(3) == 0 && ashut < 3) {
                  trg.d.gotoAndStop(6);
                } else {
                  trg.d.gotoAndStop(5);
                }
              }
            } else {
              if (trg.d._currentframe == 5) {
                sideflip(100);
                f1 = 10;
                xenf = trg.xp - player.xp;
                yenf = trg.yp - player.yp;
                if (Math.abs(xenf) > Math.abs(yenf)) {
                  yenf = 0;
                  if (xenf > 0) {
                    xenf = f1;
                    f3 = 2;
                  } else {
                    xenf = -f1;
                    f3 = 4;
                  }
                } else {
                  xenf = 0;
                  if (yenf > 0) {
                    f3 = 3;
                    yenf = f1;
                  } else {
                    f3 = 1;
                    yenf = -f1;
                  }
                }
                if (trg.d.d._currentframe < 6) {
                  trg.d.d.h.gotoAndStop(f3);
                  trg.f3 = f3;
                } else {
                  trg.d.d.h.gotoAndStop(f3 + 4);
                  trg.f3 = f3 + 4;
                }
              }
              if (trg.d.d._currentframe == 5) {
                if (trg.d._currentframe == 6) {
                  f1 = 29;
                  if (trg.alter == 2) {
                    f1 = 86;
                  }
                  if (ashut == 1) {
                    spaw(trg.xp - 50, trg.yp, 0, f1);
                    spaw(trg.xp + 50, trg.yp, 0, f1);
                  } else {
                    spaw(trg.xp, trg.yp - 50, 0, f1);
                    spaw(trg.xp, trg.yp + 50, 0, f1);
                  }
                  _root.soundy('summonsound.wav', 120);
                } else {
                  if (trg.alter == 1) {
                    shots(trg.xp, trg.yp, -xenf, -yenf, true);
                  } else {
                    shots(trg.xp, trg.yp, -xenf, -yenf, 2);
                  }
                }
              }
            }
            break;
          case 48: //Wrath
            trg.xbew *= 0.85;
            trg.ybew *= 0.85;
            walkframe();
            if (Math.abs(trg.xbew) < Math.abs(trg.ybew)) {
              trg.d.bo.gotoAndStop(1);
            } else {
              trg.d.bo.gotoAndStop(2);
            }
            sideflip(trg.xbew);
            trgnextd();
            if (trg.d._currentframe < 3) {
              if (trg.gogo) {
                if (trg.gh) {
                  trg.gogo = false;
                  trg.ypp = undefined;
                  trg.xpp = trg.ypp;
                } else {
                  trg.xbew *= 0.8;
                  trg.ybew *= 0.8;
                  trg.xbew += trg.xpp * 1.5;
                  trg.ybew += trg.ypp * 1.5;
                  outgrid(trg.til);
                  if (Math.abs(trg.xbew) > Math.abs(trg.ybew)) {
                    trg.yp *= 0.9;
                    trg.yp += yenf * 0.1;
                  } else {
                    trg.xp *= 0.9;
                    trg.xp += xenf * 0.1;
                  }
                }
              } else {
                if (trg.trg2.s > 0) {
                  trg2 = trg.trg2;
                  if (trg2.dones) {
                    trg.trg2 = undefined;
                    trg.xpp = undefined;
                  }
                  siz = 130;
                  if (enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, siz)) {
                    enf = (Math.min(1, siz - enf) / enf) * 0;
                    trg.xbew += xenf * enf;
                    trg.ybew += yenf * enf;
                    randrunx(1);
                    trg2 = trg.trg2;
                    f1 = (trg.xp - trg.xpp) * (trg.xp - trg2.xp);
                    f2 = (trg.yp - trg.ypp) * (trg.yp - trg2.yp);
                    if (f1 > 50 or f2 > 50) {
                      trg.xbew *= 0.5;
                      trg.ybew *= 0.5;
                      trg.xpp = undefined;
                    }
                  }
                } else {
                  randrunx(1);
                  if (random(Math.max(60, enfcheck(trg.xp, trg.yp, player.xp, player.yp, 10000))) == 0) {
                    trg.d.gotoAndStop(5);
                    trg.xpp = 0;
                    trg.ypp = 0;
                  } else {
                    trg.til = ingrid(trg.xp, trg.yp);
                    if (chaa()) {
                      if (random(2) == 0) {
                        trg.d.gotoAndStop(5);
                      } else {
                        trg.gogo = true;
                      }
                    }
                  }
                }
              }
            } else {
              if (trg.d._currentframe == 5 && trg.d.d._currentframe == 5) {
                outgrid(ingrid(trg.xp, trg.yp));
                f1 = 4;
                if (trg.alter == 2) {
                  f1 = 5.040000005;
                }
                trg.trg2 = create(xenf, yenf, 0, trg.xpp * 10, trg.ypp * 10, 0, f1);
                trg.trg2.d.d.gotoAndStop(1);
                if (trg.xpp != 0 or trg.ypp != 0) {
                  trg.trg2.ph = true;
                } else {
                  trg.trg2.bh = false;
                }
                trg.xpp = undefined;
                trg.trg2.wrathBomb = true;
              }
            }
            break;
          case 222:
            ++trg.fra;
            trg._visible = true;
            f1 = 1 - trg.fra / 21;
            trg.xbew = trg.xppp * f1;
            trg.ybew = trg.yppp * f1;
            if (trg.fra > 42) {
              trg.done = true;
            }
            if (enfcheck(trg.xp, trg.yp, player.xp, player.yp, 20)) {
              playerhurt(1, 39);
            }
            if (trg.f222) {
              trg.d.gotoAndStop(1);
              if (trg.xbew * trg.d._xscale < 0) {
                trg.d._xscale *= -1;
              }
            } else {
              if (trg.ybew < 0) {
                trg.d.gotoAndStop(2);
              } else {
                trg.d.gotoAndStop(3);
              }
            }
            break;
          case 39:
            if ((fra + trg.e) % 5 == 0) {
              splater(trg.xp, trg.yp + 5, 1 + random(10), Math.random() * 0.7);
            }
          case 49:
            markhere(trg);
            if (trg.d._currentframe < 3) {
              randrunx(0.7);
              walkframe();
              sideflip(trg.xbew);
              if ((fra + trg.e) % 3 == 0) {
                f1 = true;
                if (trg.s == 49) {
                  f1 = random(10) == 0;
                  if (random(7) == 0) {
                    f1 = true;
                    if (enfcheck(trg.xp, trg.yp, player.xp, player.yp, 70 + random(130))) {
                      f1 = false;
                      trg.d.gotoAndStop(11);
                    }
                  }
                }
                if (f1) {
                  if (enfcheckx(trg.xp, trg.yp, player.xp, player.yp, 400)) {
                    if (Math.abs(xenf) > Math.abs(yenf)) {
                      sideflip(-xenf);
                      f1 = 5;
                    } else {
                      if (yenf > 0) {
                        f1 = 7;
                      } else {
                        f1 = 6;
                      }
                    }
                    trg.f1 = f1;
                    f1 += trg.alter * 3 - 3;
                    trg.d.gotoAndStop(f1);
                    trg.xpp = -xenf;
                    trg.ypp = -yenf;
                  }
                }
              }
            } else {
              trgnextd();
              if (trg.d._currentframe == 11 && trg.s != 39) {
                trg.d.d.d.gotoAndStop(1);
                if (trg.d.d._currentframe == 14) {
                  quadf(trg.xp, trg.yp, 8, true);
                  if (trg.alter == 2) {
                    bossfire(5, true);
                  }
                }
              } else {
                if (trg.alter == 3) {
                  if (trg.d.d._currentframe == 18) {
                    f2 = Math.abs(trg.xpp) > Math.abs(trg.ypp);
                    if (f2) {
                      trg.ypp = 0;
                    } else {
                      trg.xpp = 0;
                    }
                    f1 = 16 / enfget(trg.xpp, trg.ypp);
                    xenf = trg.xpp * f1 * 1.4;
                    yenf = trg.ypp * f1;
                    trg2 = create(trg.xp, trg.yp, 0, xenf, yenf, 0, 222, trg.s);
                    trg.trg2 = trg2;
                    trg2.chu = true;
                    trg2.bh = false;
                    trg2.ggh = true;
                    trg2.apf = true;
                    trg2.fra = -1;
                    trg2.f222 = f2;
                    trg2.trg2 = trg;
                    trg2.xppp = xenf;
                    trg2.yppp = yenf;
                    trg2._visible = true;
                  }
                } else {
                  if (trg.d.d._currentframe > 29 && trg.d.d._currentframe < 70) {
                    lasershow(trg);
                  }
                }
              }
              if (trg.alter == 2) {
                trg.xpp = -trg.xpp;
                trg.ypp = -trg.ypp;
              }
              if (trg.d._currentframe < 3) {
                trg.xpp = undefined;
              }
            }
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            break;
          case 36:
            gurdy = true;
            for (a in ball) {
              trg2 = ball[a];
              if (trg2.flyai) {
                siz = 80;
                if (enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, siz)) {
                  enf = -(siz - enf) * 0.03 / enf;
                  trg2.xbew += xenf * enf;
                  trg2.ybew += yenf * enf;
                }
              }
            }
            trgnextd();
            if (trg.d._currentframe == 1) {
              trg.idle = !trg.idle;
              if (trg.idle) {
                if (plah) {
                  trg.d.gotoAndStop(5);
                  plah = false;
                } else {
                  trg.d.gotoAndStop(6 + random(2));
                }
              } else {
                if (random(3) != 0 && player.yp > 200 && ashut < 8 && trg.specoz != 11) {
                  enfcheck(trg.xp, trg.yp, player.xp, player.yp, 10000);
                  if (Math.abs(xenf) > Math.abs(yenf) or yenf > 0) {
                    if (xenf > 0) {
                      f1 = 10;
                    } else {
                      f1 = 11;
                    }
                  } else {
                    f1 = 9;
                  }
                  trg.d.gotoAndStop(f1);
                } else {
                  if (ashut < 14) {
                    f1 = [8, 12, 13];
                    trg.d.gotoAndStop(f1[random(f1.length)]);
                    if (ashut > 15) {
                      trg.d.gotoAndStop(13);
                    }
                  } else {
                    trg.idle = true;
                  }
                }
              }
            }
            if (trg.d.d.now) {
              switch (trg.d._currentframe) {
                case 8:
                  create(trg.xp + 60, trg.yp - 25, 0, 10, 0, 0, 14);
                  _root.soundy('summonsound.wav', 70);
                  _root.soundy('Boss_Bug_Hiss.mp', 100);
                  break;
                case 12:
                  trg2 = create(trg.xp + 40, trg.yp - 65, 0, 0, -20, 0, 18);
                  trg3 = create(trg.xp - 40, trg.yp - 65, 0, 0, -20, 0, 18);
                  _root.soundy('summonsound.wav', 100);
                  _root.soundy('Boss_Lite_HIss.mp', 100);
                  trg2.die = true;
                  trg3.die = true;
                  trg2.hp -= 2;
                  trg3.hp -= 2;
                  break;
                case 13:
                  trg2 = create(trg.xp + 42, trg.yp + 45, 0, 0, 0, 0, 30);
                  trg3 = create(trg.xp - 42, trg.yp + 45, 0, 0, 0, 0, 30);
                  _root.soundy('summonsound.wav', 120);
                  trg2.boss = true;
                  trg3.boss = true;
                  break;
                case 9:
                  shots(trg.xp + rand() * 30, trg.yp - 20, rand() * 3, 10, true);
                  _root.soundy('Boss_Lite_Gurgle.mp', 100);
                  break;
                case 10:
                  shots(trg.xp + 13, trg.yp - 18 - rand() * 30, -10, 1 + rand() * 3, true);
                  _root.soundy('Boss_Gurgle_Roar.mp', 100);
                  break;
                case 11:
                  shots(trg.xp - 13, trg.yp - 18 - rand() * 30, 10, 1 + rand() * 3, true);
                  _root.soundy('Boss_Gurgle_Roar.mp', 100);
              }
              trg.d.d.now = false;
            }
            trg.xp = trg.xpp;
            trg.yp = trg.ypp;
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
        }
      }

      function telpx(f3) {
        if (f3 == 2) {
          f2 = 120 + Math.random() * 80;
        } else {
          f2 = 250 * Math.random() + 60;
        }
        f1 = trg.xp + crand(f2);
        f2 = trg.yp + crand();
        if (f3 == 2) {
          f3 = enfcheck(f1, f2, player.xp, player.yp, 700);
          if (f3) {
            f3 = f3 > 180;
          }
        } else {
          if (!f3) {
            if (trg.alter != 2 or trg.s != 38) {
              f3 = !enfcheckx(f1, f2, player.xp, player.yp, 400) && !enfcheck(f1, f2, player.xp, player.yp, 200);
            } else {
              f3 = enfcheck(f1, f2, player.xp, player.yp, 1000);
              f4 = f3;
              f3 = f3 > 50 && f3 < 120;
            }
          } else {
            f3 = enfcheck(f1, f2, player.xp, player.yp, 10000);
            f3 = f3 > 130 && f3 < 1000;
          }
        }
        if (f3) {
          f3 = ingrid(f1, f2);
          if (levz[f3] < 0.5) {
            outgrid(f3);
            trg.xpp = xenf;
            trg.ypp = yenf;
          }
        }
      }

      function smartd() {
        switch (trg.s) {
          case 79:
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            if (trg.specoz) {
              trg.xbew *= 0.92;
              trg.ybew *= 0.92;
              if (trg.alt) {
              }
            }
            if (trg.alt) {
              trg.ggh = true;
              trg2 = trg.trg2;
              if (altboss == 2) {
                if (trg2.s != 79) {
                  trg.dones = true;
                }
                trg.invincible = true;
                bord(580, 60, 410, 170);
                if (trg.d._currentframe == 12) {
                  if (trgnextd()) {
                    trg.d.gotoAndStop(7);
                    trg.fire = 60;
                    trg.ypp = 0;
                    trg.xpp = 0;
                  }
                  if (trg.d.d._currentframe > 15 && trg.d.d._currentframe < 50) {
                    lasershow(trg);
                  }
                } else {
                  if (trg.fire > -100) {
                    if (enfcheck(trg.xp, trg.yp, player.xp, player.yp, 300)) {
                      enf = 0.65 / enf;
                      trg.xbew += xenf * enf;
                      trg.ybew += yenf * enf * 0.9;
                    }
                  } else {
                    f1 = player.yp - trg.yp;
                    trg.ybew += absmax(f1 * 0.01, 0.2);
                  }
                  --trg.fire;
                  if (trg.fire < 0) {
                    if (random(30) == 0 && trg.fire > -100) {
                      trg.fire = -101;
                      trg.ypp = 0;
                      trg.xpp = 0;
                    }
                  } else {
                    if (random(40) == 0 && trg.fire < -180) {
                      trg.fire = 60;
                    }
                  }
                  trg.d.gotoAndStop(7);
                  trg.onown = true;
                  sideflip(-trg.xbew);
                  markhere(trg);
                  if (random(10) == 0 && trg.fire < 0) {
                    chaa(2);
                    if (trg.xpp != 0 && trg.ypp == 0) {
                      trg.d.gotoAndStop(12);
                      sideflip(-trg.xpp * 10);
                    }
                  }
                }
              } else {
                if (trg2.dones or altboss && trg2.hp < 60 or trg.onown) {
                  bord(580, 60, 410, 170);
                  if (!trg.onown) {
                    trg.onown = true;
                    _root.soundy('Cute_Grunt_' + random(3) + '.mp', 100);
                  }
                  i = 0;
                  while (i < 19) {
                    trg3 = trg2['n' + i];
                    trg3._visible = false;
                    ++i;
                  }
                  if (trg.d._currentframe <= 9) {
                    trg.d.gotoAndStop(9);
                    trg.ma = 8;
                  }
                  trg.xbew /= 0.85;
                  trg.ybew /= 0.85;
                  enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
                  enf = 0.5 / enf;
                  trg.xbew -= xenf * enf;
                  trg.ybew -= yenf * enf;
                  sideflip(-trg.xbew);
                } else {
                  enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
                  enf = 0.25 / enf;
                  trg.xbew -= xenf * enf;
                  trg.ybew -= yenf * enf;
                  trgnextd();
                  if (trg.d._currentframe <= 6) {
                    trg.d.gotoAndStop(7);
                  }
                  firemode(300, 5);
                }
              }
            } else {
              if (trg.trg2 == undefined && fra < 80) {
                trg.fire = 0;
                trg.trg2 = create(trg.xp, trg.yp - 8, 0, 0, 0, 0, trg.s);
                trg2 = trg.trg2;
                trg2.fra = -100;
                trg2.alt = true;
                trg2.outway = true;
                trg2.trg2 = trg;
                if (!altboss && trg.specoz != 3) {
                  i = 0;
                  while (i < 17) {
                    trg3 = trg.attachMovie('necksegment2', 'n' + i, i);
                    ++i;
                  }
                }
              }
              if (trg.fire == 0) {
                trg.sp = 1.4;
                if (random(60) == 0 && (altboss != 2 or random(4) == 0)) {
                  ++trg.fire;
                  _root.soundy('Monster_Yell_B_' + random(2) + '.mp', 100);
                }
                trg.d.gotoAndStop(1);
              } else {
                ++trg.fire;
                if (trg.fire > 0) {
                  trg.d.gotoAndStop(2);
                  trg.sp += 0.04;
                  trg.sp *= 0.98;
                  if (trg.fire > 100) {
                    trg.fire = -100;
                  }
                } else {
                  if (altboss == 2) {
                    trg.d.gotoAndStop(1);
                    trg.fire = 0;
                  } else {
                    trg.d.gotoAndStop(5);
                    trg.sp = 0;
                  }
                }
              }
              if (altboss == 2) {
                trg.sp += 0.2;
                if (fra % 7 == 0) {
                  trg2 = parc('bloo', trg.xp, trg.yp, 0, 123);
                }
              }
              pathfind(trg, playx, playy, trg.sp);
              if (altboss == 2) {
                trg.sp -= 0.2;
              }
              f1 = 0;
              if (altboss == 2) {
                f1 = 6;
              } else {
                if (altboss) {
                  f1 = 3;
                }
              }
              if (enfget(trg.xbew, trg.ybew) > 3) {
                if (Math.abs(trg.xbew) > Math.abs(trg.ybew)) {
                  trg.d.bo.gotoAndStop(3 + f1);
                } else {
                  trg.d.bo.gotoAndStop(2 + f1);
                }
                sideflip(trg.xbew);
              } else {
                trg.d.bo.gotoAndStop(1 + f1);
              }
              trg2 = trg.trg2;
              if (trg.s == trg2.s && trg.specoz != 3) {
                enf = enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, 1000);
                f3 = 76;
                if (altboss) {
                  if (enf > 0 && !trg2.onown) {
                    f2 = ((enf - 20) / enf) * 0.1;
                    trg2.xbew += xenf * f2;
                    trg2.ybew += yenf * f2;
                  }
                } else {
                  if (enf > f3) {
                    f2 = ((enf - f3) / enf) * 0.01;
                    trg2.xbew += xenf * f2;
                    trg2.ybew += yenf * f2;
                  }
                }
                f3 += 120;
                i = 0;
                while (i < 19) {
                  trg3 = trg['n' + i];
                  f1 = (16 - i) / 18;
                  trg3._x = -xenf * f1 - 6;
                  f2 = Math.abs(i - 9) * 0.5;
                  f2 = 16 - f2 * f2;
                  f2 *= Math.max(0, f3 - enf) / f3;
                  trg3._y = -yenf * f1 - 35 + f2 * 1.5 + i * 0.8;
                  trg3._visible = true;
                  if (yenf < 0) {
                    trg3.swapDepths(60 - i);
                  } else {
                    trg3.swapDepths(3 + i);
                  }
                  ++i;
                }
                trg.n18._visible = false;
              } else {
                i = 0;
                while (i < 19) {
                  trg3 = trg['n' + i];
                  trg3._visible = false;
                  ++i;
                }
              }
            }
            break;
          case 78:
            momHeart = trg;
            trg.outway = true;
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            trg.xp = trg.xpp;
            trg.yp = trg.ypp;
            f3 = Math.min(3, 4 - Math.round((trg.hp / hps[trg.s]) * 3 + 0.45));
            if (momstate == 3) {
              splater(trg.xp + crand() * 2, trg.yp + crand(Math.random() * Math.random() * 200) + 8, 1 + random(10), Math.random() * 0.5 + 0.2);
            }
            if (momstate != f3) {
              momstate = f3;
            }
            if (trg.d._currentframe != 5 && (trg.d._currentframe != 4 or trg.d.d._currentframe > 30)) {
              trg.d.gotoAndStop(momstate);
              if (trg.downbro-- < 0 && momstate != 3) {
                trg.d.gotoAndStop(5);
                _root.soundy('heartin.wav');
              }
            } else {
              if (trg.d._currentframe == 5 or momstate == 3) {
                if (trg.fire < 40) {
                  trg.downbro = 100;
                  trg.d.gotoAndStop(4);
                  _root.soundy('heartout.wav');
                  _root.soundy('Mom_Vox_Filtered_Isaac_' + random(3) + '.mp');
                }
              }
            }
            trg.bh = trg.d._currentframe != 5 && (trg.d._currentframe != 4 or trg.d.d._currentframe > 5);
            if (ashut < 2) {
              --trg.fire;
            }
            if (momstate !== 3) {
            } else {
              if (random(2) == 0 && fra % 23 == 0) {
                green(true, true);
              }
            }
            if (trg.fire < 0) {
              if (lmo != momstate) {
                trg.wave = 0;
              }
              f5 = _root.SecretUnlocked[45];
              if (f5) {
                switch (momstate) {
                  case 1:
                    f2 = [60, 55, 20, 19];
                    break;
                  case 2:
                    f2 = [41, 59, 67, 28];
                    break;
                  case 3:
                    f2 = [61, 24, 14, 23];
                }
              } else {
                switch (momstate) {
                  case 1:
                    f2 = [60, 59, 24];
                    break;
                  case 2:
                    f2 = [55, 24, 27.4];
                    break;
                  case 3:
                    f2 = [25.5, 61, 14];
                }
              }
              f2 = f2[trg.wave];
              if (f2 == 60 && fra < 100) {
                f1 = 180;
              } else {
                f1 = 40;
              }
              _root.soundy('summonsound.wav', 100 + momstate * 10);
              create(trg.xp + f1, trg.yp, 0, 0, 0, 0, f2);
              if (f2 != 20 && f2 != 67) {
                create(trg.xp - f1, trg.yp, 0, 0, 0, 0, f2);
                if (f2 == 19) {
                  create(trg.xp + f1, trg.yp + 30, 0, 0, 0, 0, f2);
                  create(trg.xp - f1, trg.yp + 30, 0, 0, 0, 0, f2);
                  create(trg.xp + f1, trg.yp + 60, 0, 0, 0, 0, f2);
                  create(trg.xp - f1, trg.yp + 60, 0, 0, 0, 0, f2);
                } else {
                  if (f2 != 60 && f2 != 59 && f2 != 24 && f2 != 27.4 && f2 != 25.5) {
                    f1 *= 0.8;
                    if (f2 != 28) {
                      create(trg.xp, trg.yp + f1, 0, 0, 0, 0, f2);
                    }
                    create(trg.xp, trg.yp - f1, 0, 0, 0, 0, f2);
                  }
                }
              }
              trg.fire = 75;
              ++trg.wave;
              if (trg.wave > 2 && !f5 or trg.wave > 3 && f5) {
                trg.wave = 0;
              }
              lmo = momstate;
            }
            break;
          case 69:
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            trgnextd();
            switch (trg.d._currentframe) {
              case 1:
              case 2:
                randrun();
                if (random(40) == 0 && enfcheckx(trg.xp, trg.yp, player.xp, player.yp, 300)) {
                  trg.d.gotoAndStop(5);
                } else {
                  if (random(140) == 0) {
                    trg.d.gotoAndStop(9);
                  } else {
                    if (random(100) == 0) {
                      trg.d.gotoAndStop(7);
                    } else {
                      if (random(70) == 0 && ashut < 3 + random(3) && (random(3) == 0 or !altboss)) {
                        trg.d.gotoAndStop(8);
                      }
                    }
                  }
                }
                break;
              case 5:
                if (trg.d.d._currentframe == trg.d.d._totalframes - 1) {
                  trg.d.gotoAndStop(6);
                  if (trg.xpp > 0) {
                    trg.xp = trg.xpp;
                    trg.yp = trg.ypp;
                  }
                } else {
                  telpx();
                }
                break;
              case 8:
                if (trg.d.d._currentframe == 22) {
                  trg2 = create(trg.xp, trg.yp, 0, 0, 0, 0, 25);
                  _root.soundy('summonsound.wav');
                  trg2.outway = true;
                  if (altboss) {
                    trg2.alter = 2;
                  }
                }
                break;
              case 9:
                if (trg.d.d._currentframe == 26) {
                  quadf(trg.xp, trg.yp, 10, true);
                }
                break;
              case 7:
                if (trg.d.d._currentframe == 28) {
                  quadf(trg.xp, trg.yp, 10);
                }
                if (trg.d.d._currentframe == 51) {
                  quadf(trg.xp, trg.yp, 10, 2);
                }
                if (trg.d.d._currentframe == 77) {
                  quadf(trg.xp, trg.yp, 10);
                }
            }
            if (altboss) {
              sideflip((0.5 - trg.e % 2) * 10);
            }
            break;
          case 68:
            trgnextd();
            slug = trg;
            if (trg.specoz == 12 && fra % 13 == 0) {
              trg2 = parc('bloo', trg.xp, trg.yp);
              trg2._xscale *= 1.6;
              trg2._yscale = trg2._xscale;
              colorit(trg2, 0.6, 1.5, 0.2, 100, 120, 0);
            }
            switch (trg.d._currentframe) {
              case 1:
              case 2:
                randrun();
                if (trg.specoz != 12 or random(3) == 0) {
                  if (random(23) == 0) {
                    trg.d.gotoAndStop(10);
                  }
                  if (random(20) == 0) {
                    trg.d.gotoAndStop(5 + random(2));
                  }
                  if (altboss) {
                    if (Math.abs(trg.yp - 20 - player.yp - player.ybew * 5) < 20) {
                      trg.d.gotoAndStop(12);
                    }
                    if (Math.abs(trg.xp - player.xp - player.xbew * 5) < 40 && trg.yp < player.yp) {
                      trg.d.gotoAndStop(13);
                    }
                  }
                }
                break;
              case 13:
                if (trg.d.d._currentframe > 10 && trg.d.d._currentframe < 50) {
                  f8 = 15 - random(2) * 30;
                  trg.yp -= 20;
                  trg.xp -= f8;
                  lasershow(trg);
                  trg.yp += 20;
                  trg.xp += f8;
                  trg.xpp = 0;
                  trg.ypp = 1;
                }
                break;
              case 12:
                if (trg.d.d._currentframe > 10 && trg.d.d._currentframe < 50) {
                  trg.yp -= 20;
                  lasershow(trg);
                  trg.yp += 20;
                  trg.xpp = 1 - random(2) * 2;
                  trg.ypp = 0;
                }
                break;
              case 11:
                if (trg.d.d._currentframe == 28) {
                  if (altboss) {
                    z = 0;
                    while (z < 10) {
                      f1 = crand(random(100));
                      f2 = crand();
                      trg2 = parc('bloo', trg.xp + f1, trg.yp + f2);
                      trg2._xscale *= 2;
                      trg2._yscale = trg2._xscale;
                      ++z;
                    }
                    if (trg.specoz) {
                      green(false, false);
                      green(false, true);
                      green(false, true);
                    } else {
                      quadf(trg.xp, trg.yp, 10, 1);
                    }
                  } else {
                    cirf(trg.xp, trg.yp, 10, 12);
                  }
                  _root.soundy('ForestBoss_Stomps' + random(3) + '.wav', 100);
                }
                break;
              case 5:
                if (trg.d.d._currentframe == 38) {
                  if (altboss) {
                    if (trg.specoz) {
                      green(false, true);
                      green(false, true);
                    } else {
                      quadf(trg.xp, trg.yp, 10, 1);
                    }
                  } else {
                    cirf(trg.xp, trg.yp, 10, 8);
                  }
                  _root.soundy('ForestBoss_Stomps' + random(3) + '.wav', 80);
                }
                break;
              case 6:
                if (trg.d.d._currentframe > 30 && trg.d.d._currentframe < 40) {
                  if (trg.d.d._currentframe == 31) {
                    _root.soundy('Sink Drain Gurgle.wav', 100);
                    if (trg.specoz == 3) {
                      spaw(trg.xp, trg.yp, 50, 23);
                      spaw(trg.xp, trg.yp, 50, 23);
                    }
                  }
                  f1 = crand(random(100));
                  f2 = crand();
                  if (altboss) {
                    f1 *= 1.5;
                    f2 *= 1.5;
                  }
                  trg2 = parc('bloo', trg.xp + f1, trg.yp + f2);
                  trg2._xscale *= 2;
                  trg2._yscale = trg2._xscale;
                  if (!altboss) {
                    colorit(trg2, 0.6, 1.5, 0.2, 100, 120, 0);
                  } else {
                    trg2._xscale *= 1.3;
                    trg2._yscale *= 1.3;
                  }
                }
                break;
              case 10:
                if (trg.d.d._currentframe == 30) {
                  enf = enfcheck(trg.xp, trg.yp, player.xp, player.yp, 10000);
                  if (enf > 0) {
                    enf = 0.03333333333333333;
                    trg.xbew = -xenf * enf;
                    trg.ybew = -yenf * enf;
                  }
                }
            }
            trg.bh = (trg.d._currentframe != 10 or trg.d.d._currentframe < 29) && (trg.d._currentframe != 11 or trg.d.d._currentframe > 27);
            if (trg.bh) {
              if (trg.specoz == 12) {
                trg.xbew *= 0.8;
                trg.ybew *= 0.8;
              } else {
                trg.xbew *= 0.6;
                trg.ybew *= 0.6;
              }
            }
            f3 = Math.min(3, 4 - Math.round((trg.hp / hps[trg.s]) * 3 + 0.45));
            if (altboss) {
              f1 = random(10);
            } else {
              f1 = 21 + random(10);
            }
            splater(trg.xp + crand() * 2, trg.yp + crand(random(20)) + 8, f1, Math.random() * 0.5 + 0.2);
            if (_root.slugeye != f3 && fra > 30 && trg.specoz != 13 && !altboss or (trg.specoz == 13 or altboss) && _root.slugeye < 3) {
              if (trg.specoz == 13 or altboss) {
                ++_root.slugeye;
              }
              f1 = crand(30);
              f2 = crand();
              _root.soundy('plop.wav');
              trg2 = create(trg.xp + f1, trg.yp + f2, 0, f1 * 0.4, f2 * 0.4, 0, 25);
              trg2.alt = true;
              trg2.fra = -100;
              trg2.d.gotoAndStop(9);
              trg2.hp *= 200;
              trg2.invincible = true;
            }
            if (trg.specoz != 13 && !altboss) {
              _root.slugeye = f3;
            }
            if (altboss) {
              z = 0;
              while (z < 15) {
                trg2 = trg.d.d['s' + z];
                colorit(trg2, 0.7, 0.1, 0.1, 30, 0, 0);
                ++z;
              }
            }
            break;
          case 67:
            trg.ggh = true;
            duked = 65 + Math.sin(fra * 0.02) * 5;
            trg.xp = Math.min(580, Math.max(60, trg.xp));
            if (trg.xp == 580) {
              trg.xbew = -1;
            }
            if (trg.xp == 60) {
              trg.xbew = 1;
            }
            trg.yp = Math.min(410, Math.max(180, trg.yp));
            if (trg.yp == 410) {
              trg.ybew = -1;
            }
            if (trg.yp == 180) {
              trg.ybew = 1;
            }
            duke = trg;
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            trgnextd();
            if (trg.xbew > 0) {
              xenf = 1;
            } else {
              xenf = -1;
            }
            if (trg.ybew >= 0.1) {
              yenf = 1;
            } else {
              yenf = -1;
            }
            if (altboss) {
              f1 = 0.8;
              if (trg.specoz == 19) {
                f1 = 1.1;
              } else {
                if (trg.specoz) {
                  f1 = 0.5;
                } else {
                  f1 = 0.8;
                }
              }
            } else {
              f1 = 0.4;
            }
            trg.xbew += xenf * f1;
            trg.ybew += yenf * f1;
            if (trg.specoz == 6) {
              trg.xbew *= 0.9;
              trg.ybew *= 0.9;
            }
            switch (trg.d._currentframe) {
              case 1:
              case 2:
                if (random(40) == 0 && dukes + ashut < 9 && trg.specoz != 19) {
                  trg.d.gotoAndStop(5);
                } else {
                  if (random(70) == 0 && ashut - dukes * 0.5 < 5 && trg.specoz != 19) {
                    trg.d.gotoAndStop(6);
                  } else {
                    if (random(45) == 0 && dukes > 4 && ashut - dukes < 5 && trg.specoz != 5 or (trg.specoz == 5 or altboss) && random(70) == 0 or trg.specoz == 19 && random(20) == 0) {
                      trg.d.gotoAndStop(7);
                    }
                  }
                }
                break;
              case 5:
                if (trg.d.d._currentframe == 20) {
                  _root.soundy('Monster_Grunt_2_' + abr() + '.mp', 100);
                  trg2 = [];
                  f1 = 5;
                  if (trg.specoz == 16) {
                    trg2 = create(trg.xp, trg.yp + 20, 0, 0, 0, 0, 25);
                    trg2.duke = true;
                  } else {
                    trg2.push(create(trg.xp + f1 * 2, trg.yp + 20, 0, 0, 0, 0, 18));
                    trg2.push(create(trg.xp, trg.yp + 20, 0, 0, 0, 0, 18));
                    if (altboss) {
                      if (random(2) == 0) {
                        boil(true);
                      }
                    } else {
                      trg2.push(create(trg.xp - f1 * 2, trg.yp + 20, 0, 0, 0, 0, 18));
                    }
                    for (z in trg2) {
                      trg2[z].die = true;
                      trg2[z].duke = true;
                      trg2[z].fra = -20;
                    }
                  }
                }
                break;
              case 6:
                if (trg.d.d._currentframe == 18) {
                  _root.soundy('Monster_Grunt_1_' + abr() + '.mp', 100);
                  trg2 = [];
                  f5 = 5;
                  if (altboss) {
                    bossfire(10, true);
                  } else {
                    if (trg.specoz == 6) {
                      trg2.push(create(trg.xp, trg.yp + 20, 0, 0, 0, 0, 61));
                    } else {
                      if (trg.specoz == 5) {
                        trg2.push(create(trg.xp, trg.yp + 20, 0, 0, 0, 0, 80));
                      } else {
                        trg2.push(create(trg.xp, trg.yp + 20, 0, 0, 0, 0, 18));
                      }
                    }
                    for (z in trg2) {
                      trg2[z].fra = -20;
                      trg2[z].die = true;
                      if (!trg.specoz) {
                        trg2[z].d._yscale = 125;
                        trg2[z].d._xscale = 125;
                        trg2[z].hp *= 1.8;
                      }
                    }
                  }
                }
                break;
              case 7:
                trg.send = trg.d.d._currentframe == 17;
                if (trg.send) {
                  if (trg.specoz == 5) {
                    cirf(trg.xp, trg.yp, 7, 8);
                    trg.send = false;
                  } else {
                    if (altboss) {
                      cirf(trg.xp, trg.yp, 8, 8);
                    }
                  }
                  _root.soundy('Monster_Grunt_4_' + abr() + '.mp', 100);
                }
            }
            dukes = 0;
        }
      }

      function devl() {
        trg._visible = trg.d._currentframe != 1;
        if (trg.d._currentframe < 8) {
          trg.d.gotoAndStop(9);
          trg.xp = player.xp;
          trg.yp = player.yp;
          trg2 = trg.trg2;
          siz = 111;
          if (enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, siz)) {
            enf = (siz - enf) / enf;
            xenf *= enf;
            yenf *= enf;
            trg.xp += xenf;
            trg.yp += yenf;
          }
          if (ashut < 4 && random(2) == 0) {
            f1 = [55.1];
            spaw(player.xp, player.yp, 200, f1[random(f1.length)]);
          }
          if (random(2) == 0) {
            _root.soundy('satan stomp ' + random(3) + '.mp3');
          }
        }
        if (trg.trg3 != undefined) {
          if (trg.hp < trg.mhp) {
            trg.trg3.hp -= trg.mhp - trg.hp;
            trg.hp = trg.mhp;
            if (trg.trg3.hp < 0) {
              trg.trg3.done = true;
              trg.done = true;
              momkill();
            }
          }
        } else {}
        trg.bh = trg.d._currentframe == 9 && trg.d.d._currentframe > 27 && trg.d.d._currentframe < 62;
        if (trg.d._currentframe == 9 && trg.d.d._currentframe == 26) {
          trg.dmg = 300;
          gosplash();
          _root.soundy('Hellboss_Groundpound_' + random(2) + '.wav');
        }
      }

      function smartb() {
        smartd();
        switch (trg.s) {
          case 66:
            blackout = true;
            if (!trg.sic) {
              trg.xbew *= 0.8;
              trg.ybew *= 0.8;
            }
            trgnextd();
            if (trg.sic) {
              if (!trg.whut) {
                sideflip(player.xp - trg.xp);
                trg.whut = true;
                trg.d.gotoAndStop(12);
                trg.ffa = fra - enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000) * 0.1 + 80;
              } else {
                if (trg.d._currentframe < 11) {
                  trg.d.gotoAndStop(13);
                }
              }
            } else {
              if (trg.horse) {
                trg.d.gotoAndStop(8);
                if (trg.hp + 40 > death.hp) {
                  --trg.hp;
                }
              } else {
                if ((trg.whut or trg.hp / hps[trg.s] < 0.5) && trg.d._currentframe < 7) {
                  trg.xp = Math.min(580, Math.max(60, trg.xp));
                  death = trg;
                  if (!trg.whut) {
                    sideflip(player.xp - trg.xp);
                    trg.whut = true;
                    trg.d.gotoAndStop(7);
                  } else {
                    trg.d.gotoAndStop(9);
                  }
                }
              }
            }
            switch (trg.d._currentframe) {
              case 13:
                trg.xbew *= 0.975;
                trg.ybew *= 0.975;
                if (trg.alt) {
                  if (trg.ffa > fra) {
                    yenf = 0;
                    xenf = 0;
                    trg.d.d.gotoAndStop(1);
                  } else {
                    if (trg.ffa < fra - 180) {
                      trg.done = true;
                    }
                    if (!trg.whuzz) {
                      trg.whuzz = true;
                      enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
                      enf = 0.75 / enf;
                      xenf *= enf;
                      yenf *= enf;
                      trg.xpp = xenf;
                      trg.ypp = yenf;
                    } else {
                      xenf = trg.xpp;
                      yenf = trg.ypp;
                    }
                  }
                } else {
                  enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
                  enf = 0.5 / enf;
                  xenf *= enf;
                  yenf *= enf;
                }
                trg.xbew -= xenf;
                trg.ybew -= yenf;
                break;
              case 10:
                if (trg.d.d._currentframe == 16) {
                  xenf = crand(10);
                  yenf = crand();
                  if (trg.specoz) {
                    f1 = 26.1;
                  } else {
                    f1 = 41;
                  }
                  create(trg.xp + xenf, trg.yp + yenf, 0, 0, 0, 0, f1);
                  create(trg.xp - xenf, trg.yp - yenf, 0, 0, 0, 0, f1);
                  _root.soundy('summonsound.wav', 120);
                  _root.soundy('Monster_Grunt_5.mp', 100);
                }
                break;
              case 9:
                randrun();
                if (random(90) == 0 && ashut < 3) {
                  trg.d.gotoAndStop(10);
                }
                break;
              case 1:
              case 2:
                randrun();
                f1 = enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
                if (random(90) == 0 && ashut < 2 + random(2)) {
                  trg.d.gotoAndStop(5);
                } else {
                  if (random(180) == 0 && sloww <= -100 && !trg.specoz) {
                    trg.d.gotoAndStop(6);
                  } else {
                    if (random(100) == 0 && ashut < 5) {
                      trg.d.gotoAndStop(14);
                    }
                  }
                }
                break;
              case 5:
                if (trg.d.d._currentframe == 20) {
                  _root.soundy('Monster_Grunt_5.mp', 100);
                  _root.soundy('summonsound.wav', 120);
                  if (trg.specoz) {
                    xenf = crand(50);
                    yenf = crand();
                    create(trg.xp + xenf, trg.yp + yenf, 0, 0, 0, 0, 55.1);
                    create(trg.xp - xenf, trg.yp - yenf, 0, 0, 0, 0, 55.1);
                  } else {
                    i = 0;
                    while (i < 1.9) {
                      trg2 = spaw(trg.xp, trg.yp, 250 + random(100), 66);
                      if (enfcheck(trg2.xp, trg.yp, player.xp, player.yp, 150)) {
                        trg2.done = true;
                        trg2.sic = true;
                        trg2._visible = false;
                        trg2.bh = false;
                        trg.outway = true;
                        i -= 0.95;
                      } else {
                        trg2.sic = true;
                        trg2.apf = true;
                        trg2.d.gotoAndStop(12);
                        trg2.hp = 15;
                      }
                      trg.outway = true;
                      ++i;
                    }
                  }
                }
                break;
              case 6:
                if (trg.d.d._currentframe == 22) {
                  sloww = 100;
                  _root.over.gotoAndStop(7);
                }
                break;
              case 14:
                if (trg.d.d._currentframe == 18) {
                  trg2 = [];
                  trg2.push(create(20, trg.yp, 0, 0, 0, 0, 66));
                  trg2.push(create(620, trg.yp, 0, 0, 0, 0, 66));
                  trg2.push(create(trg.xp, 120, 0, 0, 0, 0, 66));
                  trg2.push(create(trg.xp, 460, 0, 0, 0, 0, 66));
                  _root.soundy('summonsound.wav', 150);
                  _root.soundy('Monster_Grunt_0_' + abr() + '.mp', 100);
                  for (z in trg2) {
                    trg2[z].sic = true;
                    trg2[z].apf = true;
                    trg2[z].d.gotoAndStop(12);
                    trg2[z].hp = 15;
                    trg2[z].outway = true;
                    trg2[z].alt = true;
                    if (enfcheck(trg2[z].xp, trg2[z].yp, player.xp, player.yp, 80)) {
                      trg2[z].dones = true;
                      trg2[z].done = true;
                    }
                  }
                }
                break;
              case 11:
                if (!trg.whuuu) {
                  _root.soundy('Monster_Yell_A_' + random(3) + '.mp', 100);
                  trg.whuuu = true;
                  trg2 = create(trg.xp, trg.yp, 0, 0, 0, 0, 66);
                  _root.soundy('summonsound.wav', 150);
                  trg2.d.gotoAndStop(8);
                  trg2.horse = true;
                  trg2.gogo = true;
                  trg2.d._xscale = trg.d._xscale;
                  trg2.apf = true;
                  trg.outway = true;
                }
                break;
              case 8:
                trg.xbew = trg.d._xscale * 0.18;
                if (trg.gogo) {
                  f1 = false;
                  if (trg.xp > 750) {
                    trg.xp = 10;
                    f1 = true;
                  } else {
                    if (trg.xp < -150) {
                      trg.xp = 630;
                      f1 = true;
                    }
                  }
                  if (f1) {
                    f1 = 95;
                    trg.yp += f1;
                    if (trg.yp > 430) {
                      trg.yp -= f1 * 3;
                    }
                  }
                }
            }
            break;
          case 65:
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            trgnextd();
            if ((trg.whut or trg.hp / trg.mhp < 0.5) && trg.d._currentframe < 9 && !altboss) {
              trg.xp = Math.min(580, Math.max(60, trg.xp));
              if (!trg.whut) {
                trg.gosplash = true;
                trg.whut = true;
                trg.d.gotoAndStop(10);
              } else {
                trg.d.gotoAndStop(9);
              }
            }
            switch (trg.d._currentframe) {
              case 9:
                trg.sp += 0.1;
                trg.sp *= 0.955;
                f1 = 1 + trg.sp * 0.1;
                trg.xbew *= f1;
                trg.ybew *= f1;
                pathfind(trg, playx, playy, trg.sp * 0.55 + 0.5);
                trg.xp = Math.min(580, Math.max(60, trg.xp));
                trg.yp = Math.min(410, Math.max(180, trg.yp));
                if (mhit(trg.xp, trg.yp)) {
                  trg.xp += crand(5);
                  trg.yp += crand(5);
                }
                sideflip(trg.xbew);
                if (trg.ffra + 10 > fra) {
                  trg.hpp = trg.hp;
                }
                if (trg.hp + 85 - trg.sp * 5 < trg.hpp) {
                  trg.d.gotoAndStop(10);
                }
                if (Math.abs(trg.xbew) > Math.abs(trg.ybew)) {
                  trg.d.bo.gotoAndStop(3);
                } else {
                  trg.d.bo.gotoAndStop(2);
                }
                break;
              case 10:
                if (trg.d.d._currentframe == 3 && trg.specoz) {
                  cirf(trg.xp, trg.yp - 50, 8, 6);
                }
                trg.ffra = fra;
                trg.hpp = trg.hp;
                trg.sp = 0.5;
                break;
              case 1:
              case 2:
                randrun();
                f1 = enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
                if (random(90) == 0 && f1 < 200) {
                  trg.d.gotoAndStop(5);
                } else {
                  if (f1 > 150 && random(200) == 0 or Math.abs(yenf) < 20 && random(30) == 0) {
                    _root.soundy('Monster_Yell_A_' + random(3) + '.mp', 100);
                    sideflip(player.xp - trg.xp);
                    trg.d.gotoAndStop(7);
                    trg.xpp = trg.xp;
                    trg.ypp = trg.yp;
                    trg.gogo = 3;
                    trg.bh = true;
                    trg._visible = trg.bh;
                  } else {
                    if (random(180) == 0) {
                      trg.d.gotoAndStop(6);
                      _root.soundy('Monster_Roar_' + random(4) + '.mp');
                    }
                  }
                }
                break;
              case 5:
                if (trg.d.d._currentframe == 5) {
                  quadf(trg.xp, trg.yp, 10, !altboss);
                }
                break;
              case 6:
                if (trg.d.d._currentframe == 30) {
                  trg.bh = false;
                  anarch = 25;
                  analt = altboss;
                  if (analt) {
                    anarch = 50;
                  }
                  if (trg.specoz) {
                    anarch = 10;
                    analt = 5;
                  }
                } else {
                  if (!trg.bh && anarch < -80) {
                    trg.bh = true;
                    trg.d.gotoAndStop(8);
                    trg.xpp = trg.xp;
                    trg.ypp = trg.yp;
                    if (player.xp > 320) {
                      trg.xp = 10;
                      sideflip(100);
                    } else {
                      sideflip(-100);
                      trg.xp = 630;
                    }
                    trg._visible = true;
                  }
                }
                if (trg.d.d._currentframe == 33) {
                  trg._visible = false;
                }
                break;
              case 8:
                if (trg.specoz) {
                  if (fra % 40 == 0 && anarch <= -80 && trg.loap) {
                    trg.loap = false;
                    trg2 = create(trg.xp, trg.yp, 0, 0, 0, 0, 5.04);
                    trg2.col = 3;
                  }
                }
                if (altboss && trg.gogo < 3 && trg.gogo > 1 && !trg.goner && fra % 8 == 0) {
                  trg.gogo -= 0.4;
                  trg2 = create(trg.xpp, random(300) + 150, 0, trg.xbew, 0, 0, 65);
                  _root.soundy('Monster_Yell_A_' + random(3) + '.mp3', 60);
                  trg2.goner = true;
                  trg2.fra = 0;
                  trg2.d._xscale = trg.d._xscale;
                  trg2.d.gotoAndStop(trg.d._currentframe);
                }
                trg.xbew = trg.d._xscale * 0.18;
                if (trg.gogo > 0) {
                  f1 = false;
                  if (trg.xp > 619) {
                    trg.xp = 10;
                    trg.xpp = 10;
                    f1 = true;
                  } else {
                    if (trg.xp < 21) {
                      trg.xp = 630;
                      trg.xpp = 630;
                      f1 = true;
                    }
                  }
                  if (f1) {
                    trg.loap = true;
                    if (altboss) {
                      if (trg.goner) {
                        trg.done = true;
                      }
                    } else {
                      f1 = 95;
                      trg.yp += f1;
                      if (trg.yp > 430) {
                        trg.yp -= f1 * 3;
                      }
                    }
                    --trg.gogo;
                  }
                } else {
                  if ((trg.xp - trg.ypp) * trg.xbew > 0) {
                    trg.d.gotoAndStop(1);
                  }
                }
            }
            break;
          case 81:
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            trgnextd();
            if ((trg.whut or trg.hp / hps[trg.s] < 0.5) && trg._xscale > 90 && trg.alter == 1) {
              if (!trg.whut) {
                trg.gosplash = true;
                trg.whut = true;
                _root.soundy('Monster_Roar_2.mp', 100);
              }
              trg.d.gotoAndStop(9);
            }
            switch (trg.d._currentframe) {
              case 1:
              case 2:
                randrunx(1);
                sideflip(trg.xbew);
                walkframe(3);
                if (random(3) == 0 or trg._xscale > 90) {
                  if (random(140 - trg.alter * 60) == 0 && (trg.alter == 1 or enfcheckx(trg.xp, trg.yp, player.xp, player.yp, 400))) {
                    if (trg.alter == 1) {
                      trg.d.gotoAndStop(7);
                    } else {
                      trg.d.gotoAndStop(6);
                    }
                    _root.soundy('Monster_Yell_B_0.mp3', 100);
                  } else {
                    if (random(20) == 0) {
                      if (enfcheck(trg.xp, trg.yp, player.xp, player.yp, 230)) {
                        sideflip(player.xp - trg.xp);
                        trg.d.gotoAndStop(5);
                      }
                    }
                  }
                }
                break;
              case 9:
                trg.bh = false;
                if (trg.d.d._currentframe == 25) {
                  _root.soundy('summonsound.wav', 200);
                  xenf = 30;
                  trg2 = create(trg.xp + xenf, trg.yp - 20, 0, 0, 0, 0, 81);
                  trg3 = create(trg.xp - xenf, trg.yp - 20, 0, 0, 0, 0, 81);
                  trg2.hp *= 0.5;
                  trg3.hp *= 0.5;
                  trg3._yscale = 75;
                  trg2._xscale = 75;
                  trg2._yscale = 75;
                  trg3._xscale = 75;
                }
                if (trg.d.d._currentframe == 65) {
                  trg.done = true;
                }
                break;
              case 5:
                if (trg.d.d._currentframe == 20 or trg.d.d._currentframe == 34) {
                  enf = enfcheck(trg.xp, trg.yp, player.xp + player.xbew * 5, player.yp + player.ybew * 5, 1000);
                  if (trg.d.d._currentframe == 20) {
                    f1 = true;
                    _root.soundy('Monster_Grunt_2_' + abr() + '.mp', 100);
                  } else {
                    f1 = 2;
                    _root.soundy('Monster_Grunt_1_' + abr() + '.mp', 100);
                  }
                  enf = enfget(xenf, yenf);
                  enf = -8.199999999999999 / enf;
                  xenf *= enf;
                  yenf *= enf;
                  shots(trg.xp, trg.yp, xenf, yenf, f1);
                }
                break;
              case 7:
                if (trg.d.d._currentframe < 7) {
                } else {
                  trg.whup = trg.hp;
                case 8:
                  enf = enfcheck(trg.xp, trg.yp, player.xp + player.xbew * 5, player.yp + player.ybew * 5, 1000);
                  enf = 1.4 / enf;
                  xenf *= enf;
                  yenf *= enf;
                  trg.xbew -= xenf;
                  trg.ybew -= yenf;
                  sideflip(player.xp - trg.xp);
                  if (trg.whup > trg.hp + trg.mhp / 8) {
                    trg.d.gotoAndStop(6);
                  }
                  break;
                case 6:
                  if (trg.d.d._currentframe > 20 && trg.d.d._currentframe < 50) {
                    trg.ypp = 0;
                    trg.xpp = random(2) - 0.5;
                    lasershow(trg);
                    trg.xpp = 0;
                    trg.ypp = random(2) - 0.5;
                    lasershow(trg);
                    trg.ypp = undefined;
                    trg.xpp = trg.ypp;
                  }
                }
            }
            break;
          case 84:
            if (!trg.app) {
              trg.app = true;
              _root.soundy('satan appear.mp');
            }
            if (trg.d._currentframe == 3 && trg.d.d._currentframe == 17) {
              _root.soundy('satan blast.mp', 50);
            }
            if (trg.d._currentframe == 8 && trg.d.d._currentframe == 83) {
              _root.soundy('satan grow.mp', 50);
            }
            trg.ybew *= 0.8;
            trg.xbew *= 0.8;
            trgnextd();
            trg.alter = 2;
            if (trg.satanPhase == 5) {
              devl();
            } else {
              if (trg.satanPhase == undefined) {
                trg.satanPhase = 1;
                trg.fire = 0;
                if (trg.satanPhase < 3) {
                  trg.bh = false;
                  trg.d.gotoAndStop(1);
                  trg.til = ingrid(trg.xp, trg.yp + 80);
                  levz[trg.til] = 1;
                }
              }
              satanBoss = trg;
              switch (trg.satanPhase) {
                case 1:
                  levz[trg.til] = 2;
                  if (trg.fire++ > 130) {
                    trg.fire = 0;
                    ++trg.satanPhase;
                    xenf = 50;
                    yenf = 110;
                    create(trg.xp, trg.yp + yenf, 0, 0, 0, 0, 81);
                    create(trg.xp + xenf, trg.yp + yenf, 0, 0, 0, 0, 55.1);
                    create(trg.xp - xenf, trg.yp + yenf, 0, 0, 0, 0, 55.1);
                    _root.soundy('satan blast.mp');
                    _root.soundy('summonsound.wav', 200);
                  }
                  if (plh) {
                    plh = false;
                    trg.d.gotoAndStop(2);
                  }
                  break;
                case 2:
                  if (helps == 1) {
                    if (trg.fire++ > 25) {
                      if (trg.d._currentframe != 3) {
                        _root.soundy('satan rise up.mp');
                        trg.d.gotoAndStop(3);
                      }
                      if (trg.d.d._currentframe > 54) {
                        ++trg.satanPhase;
                      }
                    }
                  }
                  levz[trg.til] = 1;
                  break;
                case 3:
                  mhelps = 1;
                  trg.bh = true;
                  levz[trg.til] = 0;
                  if (trg.d._currentframe < 4) {
                    trg.d.gotoAndStop(4);
                  }
                  trg.yp = Math.max(165, trg.yp);
                  switch (trg.d._currentframe) {
                    case 4:
                      yenf = Math.max(305, player.yp * 0.9300000000000001) - trg.yp - 140;
                      xenf = player.xp - trg.xp;
                      xenf1 = player.xp + player.xbew * 25 - trg.xp;
                      if (xenf * xenf1 < 0 && yenf > -70 && (trg.llo != 6 or random(10) == 0) or trg.llo == 7 && Math.abs(xenf) < 40 && random(3) == 0) {
                        trg.d.gotoAndStop(6);
                        _root.soundy('satan charge up.mp');
                        trg.llo = 6;
                      } else {
                        if (random(15) == 0 or random(3) == 0 && (trg.llo == 7 or trg.llo == 6)) {
                          trg.d.gotoAndStop(5);
                          trg.llo = 5;
                        } else {
                          if (Math.abs(xenf) > 100 or yenf < 0) {
                            trg.xbew += absmax(xenf, 15) * 0.1;
                            trg.ybew += absmax(yenf, 7) * 0.1;
                          } else {
                            if (Math.abs(xenf) > 40 && Math.abs(xenf1) < 200 && yenf >= 0) {
                              trg.d.gotoAndStop(7);
                              _root.soundy('satan charge up.mp', 50);
                              trg.llo = 7;
                            }
                          }
                        }
                      }
                      break;
                    case 5:
                      if (trg.d.d._currentframe == 56) {
                        enf = enfcheck(trg.xp, trg.yp, player.xp + player.xbew * 5, player.yp + player.ybew * 5, 1000);
                        if (enf > 300 && random(3) != 0) {
                          trg.d.d.gotoAndStop(12);
                        }
                      }
                      if (trg.d.d._currentframe == 15 or trg.d.d._currentframe == 36) {
                        enf = enfcheck(trg.xp, trg.yp, player.xp + player.xbew * 5, player.yp + player.ybew * 5, 1000);
                        if (trg.d.d._currentframe == 15) {
                          f1 = true;
                          _root.soundy('satan spit.mp', 100);
                        } else {
                          f1 = 2;
                          _root.soundy('satan spit 2.mp', 100);
                        }
                        if (enf > 300) {
                          enf = -10 / enf;
                        } else {
                          enf = -8.199999999999999 / enf;
                        }
                        xenf *= enf;
                        yenf *= enf;
                        shots(trg.xp, trg.yp, xenf, yenf, f1);
                      }
                      break;
                    case 6:
                      if (trg.d.d._currentframe > 20 && trg.d.d._currentframe < 48) {
                        trg.xpp = 0;
                        trg.ypp = 1;
                        v1 = 20;
                        lasershow(trg);
                        trg.xp -= v1;
                        lasershow(trg);
                        trg.xp += v1 + v1;
                        lasershow(trg);
                        trg.xp -= v1;
                      }
                      break;
                    case 7:
                      if (trg.d.d._currentframe > 18 && trg.d.d._currentframe < 46) {
                        trg.xpp = 0;
                        trg.ypp = 1;
                        v1 = 85;
                        trg.xp -= v1;
                        lasershow(trg);
                        trg.xp += v1 + v1;
                        lasershow(trg);
                        trg.xp -= v1;
                      }
                  }
                  break;
                case 4:
                  if (trg.app != 2) {
                    trg.app = 2;
                    _root.soundy('satan hurt.mp');
                  }
                  devl();
                  if (trg.trg2 == undefined && trg.d.d._currentframe == 50 && trg.d._currentframe == 9) {
                    trg.trg2 = create(player.xp, player.yp, 0, 0, 0, 0, 84);
                    trg2 = trg.trg2;
                    trg2.satanPhase = 5;
                    trg2._visible = false;
                    trg2.trg3 = trg;
                    trg2.trg2 = trg2.trg3;
                  }
              }
            }
            break;
          case 83:
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            trgnextd();
            switch (trg.d._currentframe) {
              case 1:
              case 2:
                trg.xp = Math.min(580, Math.max(60, trg.xp));
                randrun();
                sideflip(trg.xbew);
                f1 = enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
                if (random(30) == 0 && f1 < 200) {
                  trg.d.gotoAndStop(7);
                } else {
                  if (random(120) == 0 or Math.abs(yenf) < 20 && random(80) == 0) {
                    _root.soundy('Monster_Yell_A_' + random(3) + '.mp', 100);
                    sideflip(player.xp - trg.xp);
                    trg.d.gotoAndStop(5);
                    trg.xpp = trg.xp;
                    trg.ypp = trg.yp;
                    trg.gogo = 3;
                    trg.bh = true;
                    trg._visible = trg.bh;
                  }
                }
                break;
              case 7:
                if (trg.d.d._currentframe == 13) {
                  enf = enfcheck(trg.xp, trg.yp, player.xp + player.xbew * 5, player.yp + player.ybew * 5, 1000);
                  f1 = true;
                  _root.soundy('Monster_Grunt_2_' + abr() + '.mp', 100);
                  enf = enfget(xenf, yenf);
                  enf = -9.199999999999999 / enf;
                  xenf *= enf;
                  yenf *= enf;
                  shots(trg.xp, trg.yp, xenf, yenf, f1);
                }
                break;
              case 6:
                trg.xbew = trg.d._xscale * 0.18;
                if (trg.gogo > 0) {
                  f1 = false;
                  if (trg.xp > 619) {
                    trg.xp = 10;
                    f1 = true;
                  } else {
                    if (trg.xp < 21) {
                      trg.xp = 630;
                      f1 = true;
                    }
                  }
                  if (f1) {
                    f1 = 95;
                    trg.yp += f1;
                    if (trg.yp > 430) {
                      trg.yp -= f1 * 3;
                    }
                    --trg.gogo;
                  }
                } else {
                  if ((trg.xp - trg.ypp) * trg.xbew > 0) {
                    trg.d.gotoAndStop(1);
                  }
                }
            }
            break;
          case 82:
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            trgnextd();
            switch (trg.d._currentframe) {
              case 1:
              case 2:
                randrunx(1);
                sideflip(trg.xbew);
                walkframe(3);
                if (random(40) == 0) {
                  trg.d.gotoAndStop(5);
                }
                break;
              case 5:
                if (trg.d.d._currentframe == 9) {
                  green();
                  _root.soundy('heartout.wav', 100);
                }
            }
            break;
          case 64:
            trg.xp = Math.min(580, Math.max(60, trg.xp));
            if (trg.specoz) {
              spidboss = true;
            }
            if (fra % 3 == 0 && !trg.specoz) {
              splater(trg.xp + crand(), trg.yp + crand(random(20)), trg.spl + 1 + random(10), Math.random() * 0.5 + 0.4);
            }
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            trgnextd();
            if ((trg.whut or trg.hp / hps[trg.s] < 0.5) && trg.d._currentframe < 7) {
              if (!trg.whut) {
                trg.gosplash = true;
                trg.whut = true;
              }
              trg.d.gotoAndStop(7);
            }
            if (fra % 7 == 0) {
              trg2 = parc('bloo', trg.xp, trg.yp);
              trg2._xscale *= 2;
              trg2._yscale = trg2._xscale;
              if (trg.specoz) {
                colorit(trg2, 0, 0, 0, 235, 235, 235);
              } else {
                colorit(trg2, 0, 2, 0, 0, 40, 0);
              }
            }
            f10 = false;
            switch (trg.d._currentframe) {
              case 7:
                trg.xp = Math.min(580, Math.max(60, trg.xp));
                randrun();
                if (random(40) == 0 && ashut < 4) {
                  trg.d.gotoAndStop(9);
                } else {
                  if (random(20) == 0) {
                    if (enfcheck(trg.xp, trg.yp, player.xp, player.yp, 230)) {
                      sideflip(player.xp - trg.xp);
                      trg.d.gotoAndStop(8);
                    }
                  }
                }
                break;
              case 1:
              case 2:
                randrunx(1);
                sideflip(trg.xbew);
                walkframe(3);
                if (random(40) == 0 && ashut < 4) {
                  trg.d.gotoAndStop(6);
                } else {
                  if (random(20) == 0) {
                    if (enfcheck(trg.xp, trg.yp, player.xp, player.yp, 230)) {
                      sideflip(player.xp - trg.xp);
                      trg.d.gotoAndStop(5);
                    }
                  }
                }
                break;
              case 6:
                if (trg.d.d._currentframe == 25) {
                  _root.soundy('Monster_Grunt_5.mp', 100);
                  xenf = crand(10);
                  yenf = crand();
                  if (trg.specoz) {
                    create(trg.xp + xenf, trg.yp + yenf, 0, 0, 0, 0, 29.1);
                  } else {
                    create(trg.xp + xenf, trg.yp + yenf, 0, 0, 0, 0, 23 + random(2) * 8);
                    create(trg.xp - xenf, trg.yp - yenf, 0, 0, 0, 0, 23 + random(2) * 8);
                  }
                  _root.soundy('summonsound.wav', 120);
                }
                break;
              case 9:
                if (trg.specoz) {
                  if (trg.d.d._currentframe == 19) {
                    boil();
                    _root.soundy('Wheezy_Cough_' + random(3) + '.mp', 100);
                  }
                } else {
                  if (trg.d.d._currentframe == 25) {
                    _root.soundy('Wheezy_Cough_' + random(3) + '.mp', 100);
                    xenf = crand(10);
                    yenf = crand();
                    trg2 = create(trg.xp + trg.d._xscale * 0.4 + xenf, trg.yp + yenf, 0, 0, 0, 0, 18);
                    trg3 = create(trg.xp + trg.d._xscale * 0.4 - xenf, trg.yp - yenf, 0, 0, 0, 0, 18);
                    trg3.die = true;
                    trg2.die = trg3.die;
                    trg3.fra = -20;
                    trg2.fra = -20;
                  }
                }
                break;
              case 5:
                if (trg.d.d._currentframe == 22) {
                  f10 = true;
                }
                break;
              case 8:
                if (trg.d.d._currentframe == 9) {
                  f10 = true;
                }
            }
            if (f10) {
              if (trg.specoz) {
                trg.s = 11;
                cirf(trg.xp, trg.yp - 50, 8, 6);
                trg.s = 64;
              } else {
                green();
              }
            }
            break;
          case 63:
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            trgnextd();
            if ((trg.whut or trg.hp / trg.mhp < 0.3) && trg.d._currentframe < 8) {
              if (!trg.whut) {
                trg.gosplash = true;
                trg.whut = true;
              }
              trg.d.gotoAndStop(8);
            }
            switch (trg.d._currentframe) {
              case 8:
              case 9:
                firemode(300, 8);
                splater(trg.xp, trg.yp, trg.spl + 1 + random(10), Math.random() * 0.6 + 0.6);
                if (trg.fire <= 0) {
                  enf = enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
                  enf = 0.5 / enf;
                  trg.xbew -= xenf * enf;
                  trg.ybew -= yenf * enf;
                }
                break;
              case 1:
              case 2:
                randrun();
                if (random(40) == 0 && ashut < 3) {
                  trg.d.gotoAndStop(5);
                } else {
                  if ((Math.abs(trg.yp - player.yp) < 20 or trg.specoz && random(4) == 0) && random(5) == 0) {
                    _root.soundy('Monster_Yell_A_' + random(3) + '.mp', 100);
                    sideflip(player.xp - trg.xp);
                    trg.d.gotoAndStop(6);
                    trg.xpp = trg.xp;
                    trg.ypp = trg.yp;
                    trg.gogo = true;
                  }
                }
                break;
              case 5:
                if (trg.d.d._currentframe == 25) {
                  _root.soundy('Monster_Grunt_5.mp', 100);
                  if (trg.specoz) {
                    trg.s = 11;
                    cirf(trg.xp, trg.yp - 33, 8, 6);
                    trg.s = 63;
                  } else {
                    xenf = crand(50);
                    yenf = crand();
                    create(trg.xp + xenf, trg.yp + yenf, 0, 0, 0, 0, 14);
                    _root.soundy('summonsound.wav', 80);
                  }
                }
                break;
              case 7:
                if (trg.specoz) {
                  trg.ybew -= absmax((trg.yp - player.yp) / 100, 0.4);
                }
                trg.xbew = trg.d._xscale * 0.18;
                if (trg.gogo) {
                  if (trg.xp > 619) {
                    trg.xp = 0;
                    trg.gogo = false;
                  } else {
                    if (trg.xp < 21) {
                      trg.xp = 640;
                      trg.gogo = false;
                    }
                  }
                } else {
                  if ((trg.xp - trg.ypp) * trg.xbew > 0) {
                    trg.d.gotoAndStop(1);
                  }
                }
            }
            break;
          case 62:
            f14 = 33;
            if (altboss) {
              if (trg.d._currentframe == 6 or trg.d._currentframe == 10) {
                trg.d._yscale = 85;
                trg.d._xscale = 85;
              } else {
                trg.d._yscale = 65;
                trg.d._xscale = 65;
              }
              f14 = 26;
            }
            ++wormet;
            trg.worm = wormet;
            worm[wormet] = trg;
            if (trg.worm == 1) {
              if (trg.d._currentframe == 8 or trg.d._currentframe == 9) {
                trg.xppp = 0;
                trgnextd();
                trg.bh = true;
                trg._visible = true;
                trg.ybew = 0;
                trg.xbew = 0;
                trg.dy = 0;
                if (trg.d._currentframe == 1) {
                  trg.gogo = 3;
                  trg._visible = false;
                }
                if (trg.d.d._currentframe == 46 && trg.d._currentframe == 8) {
                  _root.soundy('Boss_Lite_HIss.mp', 100);
                  bossfire(15, true);
                } else {
                  if (trg.d._currentframe == 9) {
                    if (trg.d.d._currentframe == 23) {
                      if (!altboss) {
                        _root.soundy('Monster_Roar_2.mp', 100);
                      } else {
                        _root.soundy('Cute_Grunt_2.mp', 80);
                      }
                    }
                    if (trg.d.d._currentframe == 23 or (trg.d.d._currentframe == 24 or trg.d.d._currentframe == 25) && !altboss) {
                      if (trg.specoz == 16) {
                        cirf(trg.xp, trg.yp - 20, 8, 6);
                      } else {
                        green();
                      }
                    }
                  }
                }
              } else {
                if (!trg.whut) {
                  trg.beenx = [trg.xp];
                  trg.beeny = [trg.yp];
                  trg.beenf = [35];
                  trg.xpp = 320 - trg.xp;
                  trg.ypp = 280 - trg.yp;
                  trg.gogo = true;
                  trg.whut = true;
                }
                if (trg.ybew < -0.5) {
                  trg.d.gotoAndStop(2);
                } else {
                  trg.d.gotoAndStop(1);
                }
                if (!enfcheck(trg.xp, trg.yp, trg.beenx[0], trg.beeny[0], 3) or trg.dy > 10) {
                  trg.beenx.unshift(trg.xp);
                  trg.beeny.unshift(trg.yp);
                  trg.beenf.unshift(trg.dy);
                }
                if (trg.beenx.length > 80) {
                  f2 = [];
                  f3 = [];
                  f4 = [];
                  a = 0;
                  while (a < 50) {
                    f2[a] = trg.beenx[a];
                    f3[a] = trg.beeny[a];
                    f4[a] = trg.beenf[a];
                    ++a;
                  }
                  trg.beenx = new Array(50);
                  trg.beeny = new Array(50);
                  trg.beenf = new Array(50);
                  a = 0;
                  while (a < 50) {
                    trg.beenx[a] = f2[a];
                    trg.beeny[a] = f3[a];
                    trg.beenf[a] = f4[a];
                    ++a;
                  }
                }
                if (trg.gogo && trg.gogo != 2) {
                  if (random(2) == 0 && fra > 100 && trg.gogo != 3 && (!altboss or random(2) == 0)) {
                    trg.gogo = false;
                    if (random(2) == 0 && !altboss) {
                      trg.d.gotoAndStop(8);
                    } else {
                      trg.d.gotoAndStop(9);
                    }
                  } else {
                    enf = enfget(trg.xpp, trg.ypp);
                    trg.zp = -2 - enf * 0.02;
                    enf = 8 / enf;
                    trg.xpp *= enf;
                    trg.ypp *= enf;
                    trg.xppp = trg.xp;
                    trg.yppp = trg.yp;
                    trg.lasx = fra;
                    trg.dy = 10;
                    trg.gogo = false;
                    trg.rem = true;
                    trg.xbew = trg.xpp;
                    trg.ybew = trg.ypp;
                    f1 = 100;
                    if (altboss) {
                      f1 = 70;
                    }
                    _root.soundy('Maggot_Burst_Out_' + random(2) + '.wav', f1);
                  }
                }
                trg.dy += trg.zp;
                trg.zp += 0.4;
                if (trg.dy < f14) {
                  trg.bh = true;
                  if (trg.dy > 10 && trg.rem && trg.zp > 0) {
                    trg.rem = false;
                    trg.xppp = trg.xp;
                    trg.yppp = trg.yp;
                    trg.lasx = fra + 5;
                    f1 = 100;
                    if (altboss) {
                      f1 = 70;
                    }
                    _root.soundy('Maggot_Enter_Ground_' + random(2) + '.wav', f1);
                  }
                  trg.gogo = 2;
                  trg._visible = trg.dy < 23;
                } else {
                  trg._visible = false;
                  trg.bh = false;
                  trg.dy = f14;
                  enfcheck(trg.xp, trg.yp, player.xp, player.yp, 10000);
                  f1 = enf;
                  trg.xbew *= 0.95;
                  trg.ybew *= 0.95;
                  enf = ((250 - enf) / enf) * 0.003;
                  trg.xbew += xenf * enf;
                  trg.ybew += yenf * enf;
                  enfcheck(trg.xp, trg.yp, 320, 280, 10000);
                  enf = (Math.min(200, enf) / enf) * 0.002;
                  trg.xbew -= xenf * enf;
                  trg.ybew -= yenf * enf;
                  if (trg.zp - f1 / 20 > 15 && trg.gogo == 2 && f1 > 100) {
                    trg.xpp = player.xp;
                    trg.ypp = player.yp;
                    trg.xpp -= trg.xp;
                    trg.ypp -= trg.yp;
                    trg.gogo = true;
                  }
                }
              }
            } else {
              if (trg.worm == 7) {
                trg.bh = false;
                if (worm[1].xppp > 0) {
                  trg.ybew = 0;
                  trg.xbew = 0;
                  trg2 = worm[1];
                  if (trg2.lasx + 15 > fra) {
                    trg.d.gotoAndStop(6);
                  } else {
                    trg.d.gotoAndStop(10);
                  }
                  trg.xp = trg2.xppp;
                  trg.yp = trg2.yppp;
                  trg._visible = true;
                } else {
                  trg._visible = false;
                }
              } else {
                trg.xbew *= 0.8;
                trg.ybew *= 0.8;
                f1 = [0, 0, 4, 2, 4, 4, 5];
                if (altboss) {
                  f1 = [0, 0, 2, 2, 2, 2, 2, 2];
                }
                trg.d.gotoAndStop(f1[trg.worm]);
                if (altboss) {
                  f1 = 100;
                  f1 = [0, f1, f1, f1, f1, f1, f1];
                  f2 = [0, 0, 2, 5, 8, 11, 14];
                } else {
                  f1 = [0, 0, 100, 100, 92, 85, 100];
                  f2 = [0, 0, 3, 7, 11, 15, 18];
                }
                trg.d.d._yscale = f1[trg.worm];
                trg.d.d._xscale = trg.d.d._yscale;
                trg2 = worm[1];
                f2 = Math.min(trg2.beenx.length - 1, f2[trg.worm]);
                if (f2 > 0) {
                  trg.xp = trg2.beenx[f2];
                  trg.yp = trg2.beeny[f2];
                  trg.dy = trg2.beenf[f2];
                  if (trg.dy < f14) {
                    trg.bh = true;
                    trg._visible = trg.dy < f14 - 8;
                  } else {
                    trg._visible = false;
                    trg.bh = false;
                    trg.dy = 33;
                  }
                  if (altboss && wormet == 6) {
                    _root.tex = trg.dy;
                    if (random(2) == 0 && trg.dy < -30 && wormfo <= fra) {
                      wormfo = fra + 30;
                      quadf(trg.xp, trg.yp, 5, 2);
                    }
                  }
                } else {
                  trg._visible = false;
                  trg.bh = false;
                }
              }
            }
            trg.d.sh._y = -trg.dy;
            trg.d._y = trg.dy;
            if (altboss) {
              trg.d._y = trg.dy * 0.8 - 14;
            }
        }
      }

      function bord(f1, f2, f3, f4) {
        if (f1 == undefined) {
          f1 = 580;
          f2 = 60;
          f3 = 410;
          f4 = 160;
        }
        trg.xp = Math.min(f1, Math.max(f2, trg.xp));
        trg.yp = Math.min(f3, Math.max(f4, trg.yp));
        f5 = trg.xp == f1 or trg.xp == f2;
        f6 = trg.yp == f3 or trg.yp == f4;
        if (trg.s == 19 && altboss) {
          if (f5) {
            trg.xbew *= -1;
          }
          if (f6) {
            trg.ybew *= -1;
          }
        }
        return f5 or f6;
      }

      function cetf() {
        trg.dx = trg._rotation * 0.3;
      }

      function smarts() {
        smartsx();
        ssmarts();
        smartb();
        switch (trg.s) {
          case 89:
          case 19:
            trg2 = undefined;
            if (trg.specoz == 7) {
              trg.xbew *= 0.96;
              trg.ybew *= 0.96;
            }
            trg.outway = true;
            trg.ggh = true;
            markhere();
            if (levz[trg.til] > 1.8) {
              hurt(trg, 3);
            }
            if (!trg.donelook) {
              trg.d.gotoAndStop(7);
              trg.fail2 = 0;
              trg.donelook = true;
              for (a in ball) {
                trg2 = ball[a];
                if (trg2.s == 19 or trg2.s == 89) {
                  if (enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, roxx + 2) && trg2.trg2 != trg && trg2 != trg) {
                    trg.trg2 = trg2;
                    trg2.whop = true;
                  }
                }
              }
              trg.beenx = [];
              trg.beeny = [];
              trg.beenf = [];
              f1 = 1;
            } else {
              if (fra - trg.fra < 25) {
                if (trg.trg2.s == 19) {
                  trg.d.gotoAndStop(4);
                } else {
                  trg.d.gotoAndStop(9);
                }
              } else {
                if (trg.trg2.s == 19 or trg.trg2.s == 89) {
                  trg2 = trg.trg2;
                  trg2.trg3 = trg;
                  if (trg.specoz == 7) {
                    if (Math.abs(trg2.hp - trg.hp) > 1) {
                      f1 = (trg2.hp - trg.hp) / 2;
                      trg2.hp -= f1;
                      trg.hp += f1;
                    }
                  }
                  if (trg.s == 19) {
                    trg.d.gotoAndStop(7);
                  }
                  if (trg2.dones && trg.s == 19) {
                    trg.trg2 = undefined;
                  } else {
                    if ((trg2.dones or trg2.frei or trg.frei or trg.trg3.frei) && trg.s != 19) {
                      trg.trg3.frei = true;
                      trg.trg2 = undefined;
                      if (trg.s == 89) {
                        trg.frei = true;
                      }
                    } else {
                      if (trg2.beenx.length > 0) {
                        if (trg.specoz == 7) {
                          f0 = 6;
                        } else {
                          f0 = 4;
                        }
                        if (trg.s == 89) {
                          --f0;
                        }
                        if (trg.s == 89 && trg2.trg2 == undefined) {
                          --f0;
                        }
                        if (altboss && trg.s == 19) {
                          --f0;
                        }
                        f0 = Math.min(f0, trg2.beenx.length - 1);
                        enf = enfcheck(trg.xp, trg.yp, trg2.beenx[f0], trg2.beeny[f0], 1000);
                        f2 = 10;
                        if (enf < f2) {
                          f3 = trg2.beenx[f0];
                          f4 = trg2.beeny[f0];
                          if (altboss && trg.s == 19) {
                            if (f4 != trg.yp or f3 != trg.xp) {
                              if (f3 > trg.xp) {
                                f1 = 1;
                              } else {
                                f1 = -1;
                              }
                              if (f4 > trg.yp) {
                                f2 = 1;
                              } else {
                                f2 = -1;
                              }
                              trg._rotation = 15 * f2 * f1;
                              cetf();
                            }
                          }
                          trg.xp = f3;
                          trg.yp = f4;
                          f1 = trg2.beenf[f0];
                        } else {
                          enf = f2 / enf;
                          xenf *= enf;
                          yenf *= enf;
                          trg.xp -= xenf;
                          trg.yp -= yenf;
                          getf();
                          trg2.beenx.push(trg2.beenx[f0] + xenf);
                          trg2.beeny.push(trg2.beeny[f0] + yenf);
                          trg2.beenf.push(f1);
                        }
                        trg2.whop = true;
                      }
                    }
                  }
                } else {
                  if (!trg.whop && trg.s != 89) {
                    if (trg.fail2++ > 10) {
                      trg.dones = true;
                    }
                  } else {
                    if (!trg.hpu) {
                      trg.hpu = true;
                      if (trg.specoz != 7) {
                        if (trg.s != 89) {
                          trg.hp += 25;
                        }
                      }
                    } else {
                      if (trg.fire <= 30) {
                        if (trg.s == 19) {
                          trg.d.gotoAndStop(1);
                        }
                        if (altboss && trg.s == 19) {
                          if (enfget(trg.xbew, trg.ybew) < 0.4) {
                            trg.xbew += crand(0.1);
                            trg.ybew += crand(0.1);
                          }
                          if (trg.xbew > 0) {
                            f1 = 1;
                          } else {
                            f1 = -1;
                          }
                          if (trg.ybew > 0) {
                            f2 = 1;
                          } else {
                            f2 = -1;
                          }
                          if (Math.abs(trg.ybew) > Math.abs(trg.xbew)) {
                            trg._rotation = 0;
                          } else {
                            trg._rotation = 15 * f2 * f1;
                          }
                          cetf();
                          trg.xbew *= 0.85;
                          trg.ybew *= 0.85;
                          if (trg.gor) {
                            trg.xbew += f1 * 3;
                            trg.ybew += f2 * 1.6;
                          } else {
                            trg.xbew += f1 * 1.8;
                            trg.ybew += f2 * 3;
                          }
                          if (bord() && random(10) == 0) {
                            trg.gor = random(2) == 0;
                          }
                        } else {
                          randrunx(2);
                        }
                        killshit(trg.nextl);
                        xenf = trg.xbew;
                        yenf = trg.ybew;
                        getf();
                        if (trg.specoz == 3 && random(3) == 0) {
                          firewalk();
                        }
                      } else {
                        --trg.fire;
                      }
                    }
                  }
                }
                if (!enfcheck(trg.xp, trg.yp, trg.beenx[0], trg.beeny[0], 3)) {
                  trg.beenx.unshift(trg.xp);
                  trg.beeny.unshift(trg.yp);
                  trg.beenf.unshift(f1);
                }
              }
            }
            if (trg.s == 19) {
              trg.d.d.d.gotoAndStop(f1);
            } else {
              if (trg2.s == 89) {
                enfcheck(trg2.xp, trg2.yp, trg.xp, trg.yp, 1000);
                getf();
              }
              f2 = [0, 2, 6, 1, 5];
              trg.d.gotoAndStop(f2[f1]);
            }
            if (trg.beenx.length > 10) {
              f2 = [];
              f3 = [];
              f4 = [];
              a = 0;
              while (a < 7) {
                f2[a] = trg.beenx[a];
                f3[a] = trg.beeny[a];
                f4[a] = trg.beenf[a];
                ++a;
              }
              trg.beenx = new Array(7);
              trg.beeny = new Array(7);
              trg.beenf = new Array(7);
              a = 0;
              while (a < 7) {
                trg.beenx[a] = f2[a];
                trg.beeny[a] = f3[a];
                trg.beenf[a] = f4[a];
                ++a;
              }
            }
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            if (random(16) == 0 && trg.s == 19) {
              splater(trg.xp, trg.yp, trg.spl + 1 + random(10), Math.random() * 0.6 + 0.6);
            }
            if (trg.s == 19 && !altboss) {
              if (trg.whop > 0) {
              } else {
                if (_root.lev != _root.arenaRoom && fra > 20 && (random(100) == 0 or random(20) == 0 && trg.whop < 0)) {
                  f1 = 5;
                  f2 = ingrid(trg.beenx[f1], trg.beeny[f1]);
                  if (trg.specoz != 7) {
                    turd('breakblock', f2, true);
                  }
                }
              }
            }
            trg.whop = false;
            break;
          case 22:
            trg.pbh = fra % 2 == 0;
            if (trg.d._currentframe < 3) {
              angstfind();
              sideflip(trg.xbew);
              walkframe(2);
              trg.xbew *= 0.8;
              trg.ybew *= 0.8;
            } else {
              trgnextd();
            }
            if (trg.needmove > 0 && trg.fire-- <= 0 && ashut < random(5) + 4) {
              enf = enfcheck(trg.xp, trg.yp, player.xp, player.yp, 300);
              if (enf) {
                if (linecheckxx(trg.xp, trg.yp, player.xp, player.yp)) {
                  trg.fire = 75;
                  trg.d.gotoAndStop(5);
                  sideflip(-xenf);
                  f1 = trg.xp;
                  f2 = trg.yp;
                  enf = -7 / enf;
                  xenf *= enf;
                  yenf *= enf;
                  var trg2 = create(f1, f2, 0, xenf, yenf, 0, 18);
                  _root.soundy('Wheezy_Cough_' + random(3) + '.mp', 100);
                  trg2.fra -= 20;
                  trg2.die = true;
                  trg2.pbh = true;
                } else {
                  trg.fire = 7;
                }
              } else {
                trg.fire = 3;
              }
            }
            break;
          case 16:
            trg.pbh = fra % 2 == 0;
            if (trg.d._currentframe < 3) {
              if (trg.alter == 3) {
                pathfind(trg, playx, playy, 1.2);
                if (fra % 5 == 0) {
                  if (enfcheck(trg.xp, trg.yp, player.xp, player.yp, 40)) {
                    trg.dones = true;
                  }
                }
                trg.xbew *= 0.9;
                trg.ybew *= 0.9;
              } else {
                angstfind();
                trg.xbew *= 0.8;
                trg.ybew *= 0.8;
              }
              sideflip(trg.xbew);
              walkframe(2);
              if (trg.needmove > 0) {
                trg.d.hx.gotoAndStop(2);
                trg.d.d.hx.gotoAndStop(2);
              } else {
                trg.d.hx.gotoAndStop(1);
                trg.d.d.hx.gotoAndStop(1);
              }
              if (trg.gh && random(300) == 0) {
                if (trg.alter == 3) {
                } else {
                  trg.d.gotoAndStop(5);
                }
              }
            } else {
              trg.xbew *= 0.8;
              trg.ybew *= 0.8;
              trgnextd();
              if (trg.d.d._currentframe > 20) {
                trg.dones = true;
                if (trg.alter != 3) {
                  quadf(trg.xp, trg.yp, 7);
                }
              }
            }
            break;
          case 17:
            randrun();
            if ((fra + trg.e) % 3 == 0) {
              splater(trg.xp, trg.yp, 1 + random(10), Math.random() * 0.9 + 0.5);
            }
            trg.xbew *= 0.6;
            trg.ybew *= 0.6;
            break;
          case 15:
            trg.pbh = fra % 2 == 0;
            trgnextd();
            if (trg.alter == 2) {
              blackout = 2;
            }
            if ((fra + trg.e) % 5 == 0) {
              splater(trg.xp, trg.yp, 1 + random(10), Math.random() * 0.7 + 0.5);
            }
            trg.xbew *= 0.9;
            trg.ybew *= 0.9;
            switch (trg.mode) {
                trg.modedone = false;
                trg.mode = random(2) + 1;
                trg.mof = fra;
              case 1:
                if (trg.d._currentframe == 1 && trg.modedone or random(30) == 0 && fra - trg.mof > 30) {
                  trg.mode = 2;
                  trg.modedone = false;
                } else {
                  trg.d.gotoAndStop(5);
                  if (trg.d.d._currentframe > 8 && !trg.modedone) {
                    if (trg.alter == 3) {
                      quadf(trg.xp, trg.yp, 7, true);
                    } else {
                      if (trg.alter == 2) {
                        quadf(trg.xp, trg.yp, 7, 2);
                      } else {
                        quadf(trg.xp, trg.yp, 7);
                      }
                    }
                    trg.modedone = true;
                  }
                }
                break;
              case 2:
                trg.mof = fra;
                randrun();
            }
            break;
            break;
          case 38:
            markhere(trg);
            trg.xbew *= 0.7;
            trg.ybew *= 0.7;
            if (trg.d._currentframe <= 5) {
              if (random(10) == 0) {
                splater(trg.xp, trg.yp, random(10), Math.random() * 0.3 + 0.2);
              }
              trgnextd();
              firemode(200, 5);
              if (enfcheckx(trg.xp, trg.yp, player.xp, player.yp, 400) or trg.telp > 20) {
                ++trg.telp;
              }
              trg.telp += Math.random() * 0.1;
              if (trg.telp > 20) {
                if (trg.xpp == undefined) {
                  telpx();
                }
                if (trg.xpp == undefined) {
                  telpx();
                }
                if (trg.d._currentframe == 1 && trg.telp > 40 && trg.xpp != undefined) {
                  trg.d.gotoAndStop(6);
                }
              }
              trg.bh = true;
            } else {
              trg.bh = false;
              trgnextd();
              if (trg.d._currentframe == 1 && trg.xpp != undefined) {
                trg.d.gotoAndStop(7);
                trg.xp = trg.xpp;
                trg.yp = trg.ypp;
                trg.xpp = undefined;
                trg.telp = 0;
              }
            }
            if (trg.fire <= 0) {
              enf = enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
              enf = 0.33 / enf;
              trg.xbew -= xenf * enf;
              trg.ybew -= yenf * enf;
            }
            break;
          case 59:
            markhere(trg);
            trg.xbew *= 0.65;
            trg.ybew *= 0.65;
            f1 = false;
            f2 = trgnextd();
            if (f2 == 2 or f2 == 5) {
              trg.d.gotoAndStop(6);
            }
            if ((trg.d._currentframe == 2 or trg.d._currentframe == 5) && trg.d.d._currentframe == 29 or trg.d._currentframe == 6 && trg.d.d._currentframe == 5) {
              _root.soundy('Meat_jumps' + random(5) + '.wav');
            }
            if (trg.d._currentframe == 1) {
              f1 = true;
              if (random(30) == 0) {
                if (enfcheck(trg.xp, trg.yp, player.xp, player.yp, 200)) {
                  trg.d.gotoAndStop(8);
                }
              }
              if (random(20) == 0) {
                enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
                enf = 100 / enf;
                posw(trg.xp - xenf * enf, trg.yp - yenf * enf, 0);
                trg.xpp = xenf;
                trg.ypp = yenf;
                if (trg.yp > trg.ypp) {
                  trg.d.gotoAndStop(2);
                } else {
                  trg.d.gotoAndStop(5);
                }
                trg.f1 = 0;
                f1 = false;
              }
            } else {
              if (trg.d._currentframe == 2 or trg.d._currentframe == 5) {
                if (trg.d.d._currentframe > 4) {
                  trg.bh = trg.d.d._currentframe < 27;
                  if (trg.d.d._currentframe > 27) {
                    if (trg.d.d._currentframe == 29) {
                      quadf(trg.xp, trg.yp + 10, 7, 2);
                      _root.soundy('meatheadshoot' + fra % 3 + '.wav');
                    }
                    telpx(true);
                  } else {
                    trg.f1 = Math.min(1, trg.f1 * 1.07 + 0.005);
                    trg.xp = trg.xpp * trg.f1 + trg.xp * (1 - trg.f1);
                    trg.yp = trg.ypp * trg.f1 + trg.yp * (1 - trg.f1);
                  }
                }
                f1 = false;
              } else {
                if (trg.d._currentframe == 6) {
                  f1 = true;
                } else {
                  if (trg.d._currentframe == 8) {
                    if (trg.d.d._currentframe == 9) {
                      _root.soundy('heartout.wav', 70);
                      green();
                    }
                    f1 = true;
                  }
                }
              }
            }
            if (f1) {
              trg.bh = trg.d._currentframe != 2 && trg.d._currentframe != 5 or trg.d.d._currentframe < 30;
              trg.xp = trg.xpp;
              trg.yp = trg.ypp;
            }
            break;
          case 60:
            if (trg.d._currentframe != 5) {
              trg.d.gotoAndStop(1);
            }
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
            trg.xp = trg.xpp;
            trg.yp = trg.ypp;
            if (trg.d._currentframe == 1) {
              f1 = rotget(trg.xp - player.xp - player.xbew * 1, trg.yp - player.yp - player.xbew * 1) - 90;
              f1 -= trg.rp;
              enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
              f2 = 3 + trg.alter * 3 - enf / 330;
              f1 = absmax(rotrund(f1), f2);
              if (Math.abs(f1) < f2 / 2 && random(10) == 0) {
                trg.d.gotoAndStop(5);
              }
              trg.rp += f1;
            } else {
              if (trg.d._currentframe == 5) {
                if (trgnextd(trg.d.d.d)) {
                  trg.d.gotoAndStop(1);
                }
                if (trg.d.d.d.doit) {
                  trg.d.d.d.doit = false;
                  lasershowx(trg.rp * p180);
                }
                trg.d.d.d._rotation = trg.rp;
              }
            }
            trg.d.hx._rotation = trg.rp;
            break;
          case 90:
            bord(580, 60, 410, 170);
          case 26:
            if (trg.s == 26) {
              bord(580, 60, 410, 170);
            }
            trg.outway = false;
            if (random(10) == 0) {
              splater(trg.xp, trg.yp, random(10), Math.random() * 0.5 + 0.4);
            }
            if (trg.fire <= 0 or trg.s == 90 && trg.d._currentframe < 3) {
              enf = enfcheck(trg.xp, trg.yp, player.xp, player.yp, 1000);
              enf = 0.13 / enf;
              if (trg.alter == 2 && trg.s == 26) {
                enf *= 3;
              }
              trg.xbew -= xenf * enf;
              trg.ybew -= yenf * enf;
            }
            trg.xbew *= 0.9300000000000001;
            trg.ybew *= 0.9300000000000001;
          case 56:
          case 12:
          case 27:
          case 42:
            if (trg.s == 27) {
              if (trg.d._currentframe == 5 && (trg.d.d._currentframe == 9 or trg.d.d._currentframe == 55)) {
                _root.soundy('animal_squish' + random(3) + '.wav', 100);
              }
            }
            f1 = 4;
            if (trg.s == 42) {
              trg.xp = trg.xpp;
              trg.yp = trg.ypp;
              f1 = 12;
              levz[trg.til] = 3;
            }
            if (justnow > 30 && trg.s == 42) {
              trg.d.gotoAndStop(3);
            } else {
              if (trg.s != 26 && trg.s != 90) {
                trg.xbew *= 0.7;
                trg.ybew *= 0.7;
              }
              if (trg.s != 56 or trg.d.d._currentframe != 22 or trg.fire > 0) {
                trgnextd();
              } else {
                if (random(50) == 0) {
                  trg.d.gotoAndStop(5);
                  trg.d.d.gotoAndStop(49);
                }
              }
              if (trg.alter != 2 or trg.s != 26) {
                firemode(200, f1);
              }
            }
            if (trg.s == 56) {
              markhere(trg);
              if (trg.whuz) {
                if (trg.d._currentframe < 3) {
                  trg.d.gotoAndStop(2);
                  trg.bh = false;
                  telpx();
                  if (random(20) == 0) {
                    trg.d.gotoAndStop(5);
                  }
                } else {
                  trg.bh = true;
                }
              } else {
                trg.whuz = true;
                trg.d.gotoAndStop(5);
                trg.d.d.gotoAndStop(21);
              }
              trg.bh = trg.d._currentframe != 5 or trg.d.d._currentframe > 11 && trg.d.d._currentframe < 54;
              if (trg.d._currentframe == 5 && (trg.d.d._currentframe == 11 or trg.d.d._currentframe == 54)) {
                _root.soundy('Meat_jumps' + random(5) + '.wav');
              }
            }
            if (trg.s == 56) {
              trg.xp = trg.xpp;
              trg.yp = trg.ypp;
            }
            if (trg.s == 42) {
              levz[trg.til] = 2;
            }
            break;
          case 26.5:
            trg.s = 26;
            trg._visible = true;
            trg.bh = true;
            if (random(10) == 0 && trg._visible) {
              splater(trg.xp, trg.yp, random(10), Math.random() * 0.5 + 0.2);
            }
            break;
          case 11:
            if (!trg.bnuts) {
              trg.d.bb._visible = false;
            } else {
              firewalk();
            }
            if (random(10) == 0) {
              splater(trg.xp, trg.yp, random(10), Math.random() * 0.5 + 0.4);
            }
            trg.xbew *= 0.75;
            trg.ybew *= 0.75;
            randrun();
            walkframe(2);
            sideflip(trg.xbew);
            break;
          case 35:
            trg.phb = true;
            if (trg.trg2 == undefined) {
              trg.trg2 = create(trg.xp, trg.yp, 0, 0, 0, 0, 26);
              trg.trg2.outway = true;
              trg2.trg2 = trg;
            } else {
              trg2 = trg.trg2;
              if (trg2.hp <= 0 or random(1000) == 0) {
                trg.gosplash = true;
                attach(trg, 11);
                trg.s = 11;
                trg.outway = true;
                trg.hp = hps[trg.s];
                splater(trg.xp, trg.yp, random(10) + 1, Math.random() + 0.6);
              } else {
                trg2.d._xscale = trg.d._xscale;
                trg2.d.gotoAndStop(6);
                trg2.fra = -100;
                trg2.s = 26.5;
                trg2.pbh = true;
                trg2.alter = 1;
                --trg.fire;
                if (trg.d._currentframe < 3) {
                  trg2.xp = trg.xp;
                  trg2.yp = trg.yp;
                  trg2.ybew = 0;
                  trg2.xbew = 0;
                  trg2._visible = false;
                  trg2.bh = false;
                  if (fra % 4 == 0) {
                    enf = enfcheck(trg.xp, trg.yp, player.xp + player.xbew * 1.5, player.yp + player.ybew * 1.5, 130);
                    if (enf) {
                      trg.see = true;
                      if (trg.lastv) {
                        enf = 14 / enf;
                        trg2.xbew = -xenf * enf;
                        trg2.ybew = -yenf * enf;
                        trg.d.gotoAndStop(6);
                        trg.fire = 30;
                        _root.soundy('meatheadshoot' + random(3) + '.wav');
                      }
                    } else {
                      trg.see = false;
                    }
                  }
                }
                if (trg.d._currentframe >= 3) {
                  enf = enfcheck(trg.xp, trg.yp, trg2.xp, trg2.yp, 30000);
                  if (enf < 5 && trg.fire < 15) {
                    trg.d.gotoAndStop(1);
                  } else {
                    if (trg.d._xscale < 0) {
                      xenf = -xenf;
                    }
                    i = 0;
                    while (i < 9) {
                      trg3 = trg.d['n' + i];
                      f1 = (7 - i) / 8;
                      trg3._x = -xenf * f1;
                      f2 = Math.abs(i - 4);
                      f2 = 16 - f2 * f2;
                      f3 = 100;
                      f2 *= Math.max(0, f3 - enf) / f3;
                      trg3._y = -yenf * f1 - 25 + f2 + i - 6;
                      trg3._visible = true;
                      ++i;
                    }
                    if (trg.d._xscale < 0) {
                      xenf = -xenf;
                    }
                    enf = 0.7 / enf;
                    trg2.xbew += xenf * enf;
                    trg2.ybew += yenf * enf;
                    f1 = 0.9 + trg.fire * 0.0028;
                    trg2.xbew *= f1;
                    trg2.ybew *= f1;
                    trg2._visible = true;
                    trg2.bh = true;
                  }
                }
              }
            }
          case 87:
          case 58:
          case 24:
          case 10:
            gochar = trg.s != 58;
            if (trg.s != 35) {
              f1 = trgnextd();
              if (trg.d._currentframe == 6 && trg.s == 58) {
                telpx(true);
              }
              if (f1 == 6 && trg.s == 58) {
                if (trg.xpp != undefined) {
                  trg.xp = trg.xpp;
                  trg.yp = trg.ypp;
                  trg.d.gotoAndStop(5);
                  trg.xpp = undefined;
                }
              }
            }
            if (trg.s == 58) {
              trg.bh = (trg.d._currentframe != 5 or trg.d.d._currentframe > 3) && (trg.d._currentframe != 6 or trg.d.d._currentframe < 7);
              if (trg.d._currentframe == 5 && trg.d.d._currentframe == 3 or trg.d._currentframe == 6 && trg.d.d._currentframe == 7) {
                _root.soundy('Meat_jumps' + random(5) + '.wav');
              }
            }
            if (trg.d._currentframe < 3) {
              if (random(10) == 0 && trg.s != 10) {
                if (trg.s == 87) {
                  splater(trg.xp, trg.yp, random(10) + 31, Math.random() * 0.5 + 0.2);
                } else {
                  splater(trg.xp, trg.yp, random(10), Math.random() * 0.5 + 0.2);
                }
              }
              walkframe();
              if (trg.s == 58) {
                pathfind(trg, playx, playy, 0.8);
              } else {
                if (trg.s == 24) {
                  pathfind(trg, playx, playy, 0.4 + trg.alter * 0.35);
                } else {
                  pathfind(trg, playx, playy, 0.6);
                }
              }
              sideflip(trg.xbew);
              if (trg.s == 87) {
                if (random(60) == 0) {
                  if (enfcheck(trg.xp, trg.yp, player.xp, player.yp, 130)) {
                    trg.d.gotoAndStop(5);
                    sideflip(-xenf);
                  }
                }
              }
              if (trg.s == 58) {
                if (random(30) == 0 && !trg.lastv) {
                  trg.d.gotoAndStop(6);
                }
              }
            } else {
              if (trg.s == 87 && trg.d._currentframe == 5 && trg.d.d._currentframe == 5) {
                green();
                _root.soundy('heartout.wav', 70);
              }
              if (trg.alter == 2) {
                if (enfcheck(trg.xp, trg.yp, player.xp, player.yp, 200)) {
                  enf = 0.5 / enf;
                  trg.xbew += xenf * enf;
                  trg.ybew += yenf * enf;
                }
                trg.xbew *= 0.83;
                trg.ybew *= 0.83;
              } else {
                trg.xbew *= 0.7;
                trg.ybew *= 0.7;
              }
            }
        }
      }

      function physix() {
        for (e in ball) {
          trg = ball[e];
          f1 = 1;
          if (trg.s < 5) {
            if (sloww > -40) {
              f1 = Math.max(0.75, 0.5 - sloww / 80);
              if (sloww > 0) {
                trg.free = true;
              }
            } else {
              f1 = 1;
            }
          } else {
            if (slow > -40) {
              f1 = Math.max(0.5, 0.5 - slow / 80);
              if (slow > 0) {
                trg.free = true;
              }
            } else {
              if (trg.spid > 0) {
                --trg.spid;
                trg.xbew *= 0.7;
                trg.ybew *= 0.7;
              }
            }
          }
          if (trg.s == 7 or trg.s == 8) {
            if (Math.abs(trg.ybew) <= 0) {
              trg.ybew = trg.ypp * 0.7;
            }
          }
          if (trg.frezz <= 0 or scare > 0) {
            if (f1 == 1) {
              trg.xp += trg.xbew;
              trg.yp += trg.ybew;
            } else {
              trg.xp += trg.xbew * f1;
              trg.yp += trg.ybew * f1;
            }
          }
          trg.rr = 0;
          trg.yb = 0;
          trg.xb = 0;
        }
        for (e in ball) {
          trg = ball[e];
          if (trg.dones) {
            trg.ybew = 0;
            trg.xbew = 0;
            trg2 = undefined;
            if (trg.s == 9) {
              if (trg.bomb) {
                bomf.push([trg.xp, trg.yp, true, trg.pois]);
              } else {
                trg2 = parc('bloodsplash', trg.xp, trg.yp + trg.d._y, random(360), trg.d._xscale, trg.dpppp + 123);
                if (trg.colo) {
                  var v2 = new flash.geom.Transform(trg2);
                  v2.colorTransform = trg.colo;
                }
                if (blackout == 2) {
                  colorit(trg2, 0, 0, 0, 0, 0, 0);
                }
              }
              trg.done = true;
            }
            switch (trg.s) {
                break;
              case 1:
              case 43:
              case 20:
                trg.d.gotoAndStop(5);
                trg2 = trg.d.d;
                if (trg2._currentframe < 66 && fra % 10 == 0) {
                  trg.lasts = trg2._currentframe < 55;
                  gosplash();
                }
                break;
              case 5:
                trg2 = trg.d.d.d;
                break;
              case 2:
                if (trg.bomb) {
                  trg.spl = 30;
                  if (trg.ipecacBomb) {
                    trg.poisonBombPower = 20;
                  } else {
                    trg.poisonBombPower = 300;
                  }
                  trg.dfr = true;
                  trg.s = 4;
                  attach(trg, 4);
                  trg.d.gotoAndStop(5);
                  trg2 = undefined;
                } else {
                case 9:
                  if (!trg.dsound) {
                    trg.dsound = true;
                    _root.soundy('TearImpacts' + random(3) + '.mp', 85);
                  }
                case 7:
                case 8:
                  if (trg.s != 4) {
                    if ((random(30) == 0 or trg.spll) && (!trg.firstt or !trg.tooth)) {
                      splater(trg.xp, trg.yp, trg.spl + 1 + random(10), Math.random() * 0.8 + 0.1);
                    }
                    if (!trg.firstt) {
                      trg.firstt = true;
                      if (trg.tooth) {
                        trg.d._rotation = random(60) - 30;
                        if (random(2) == 0) {
                          trg.d._xscale *= -1;
                        }
                      } else {
                        trg.d._rotation = random(360);
                      }
                    }
                    trg2 = trg.d;
                  }
                  break;
                case 19:
                  if (_root.levz[_root.lev] <= 0) {
                    f1 = true;
                    for (a in ball) {
                      trg2 = ball[a];
                      if (trg2.s == 19 && !trg2.dones) {
                        f1 = false;
                      }
                    }
                    if (f1) {
                      trg.bossd = true;
                    }
                  }
                default:
                  if (trg.s == 77) {
                    trg.d.gotoAndStop(14);
                  } else {
                    if (trg.s == 76) {
                      trg.d.gotoAndStop(12);
                    } else {
                      if (trg.s == 73) {
                        trg.d.gotoAndStop(9);
                      } else {
                        if (trg.s == 72) {
                          trg.d.gotoAndStop(6);
                        } else {
                          if (trg.s == 28) {
                            trg.d.gotoAndStop(trg.mag + 6);
                          } else {
                            if (!trg.dfr) {
                              trg.d.gotoAndStop(3);
                            }
                          }
                        }
                      }
                    }
                  }
                  trg2 = trg.d.d;
                  if (trg.s == 102) {
                    if (trg2._currentframe == 17) {
                      _root.soundy('superholy.wav', 200);
                    }
                  } else {
                    if (trg.s == 100) {
                      if (trg2._currentframe == 66 or trg2._currentframe == 15 or trg2._currentframe == 18 or trg2._currentframe == 21 or trg2._currentframe == 24 or trg2._currentframe == 28 or trg2._currentframe == 32 or trg2._currentframe == 38 or trg2._currentframe == 44 or trg2._currentframe == 51 or trg2._currentframe == 75) {
                        trg.lasts = trg2._currentframe < 70;
                        splater(trg.xp, trg.yp, random(10) + 1 + trg.spl, 1 + Math.random() * 2);
                        gosplash();
                      }
                    } else {
                      if (trg.s == 99) {
                        if (trg2._currentframe == 66 or trg2._currentframe == 3 or trg2._currentframe == 6 or trg2._currentframe == 9 or trg2._currentframe == 12 or trg2._currentframe == 15 or trg2._currentframe == 19 or trg2._currentframe == 35) {
                          trg.lasts = trg2._currentframe < 60;
                          splater(trg.xp, trg.yp, random(10) + 1 + trg.spl, 1 + Math.random() * 2);
                          gosplash();
                        }
                      } else {
                        if (trg.s == 28) {
                          if (trg2._currentframe > 70 - trg.mag * 18 && trg2._currentframe < 84 - trg.mag * 21 && fra % 5 == 0) {
                            splater(trg.xp, trg.yp, random(10) + 1 + trg.spl, 1 + Math.random() * 2);
                            gosplash();
                          }
                        } else {
                          if (trg.s == 36) {
                            if (trg2._currentframe < 80 && fra % 7 == 0) {
                              splater(trg.xp, trg.yp, random(10) + 1 + trg.spl, 1 + Math.random() * 3.5);
                              gosplash();
                            }
                          } else {
                            if (!trg.firsttx) {
                              trg.firsttx = true;
                              gosplash();
                            }
                          }
                        }
                      }
                    }
                  }
                  f1 = Math.random() * 0.7 + 0.4;
                  if (trg.s == 14) {
                    f1 *= 0.7;
                  }
                  if (trg2._currentframe <= 3) {
                    splater(trg.xp, trg.yp, random(10) + 1 + trg.spl, f1);
                  }
                }
            }
            if (trg2._currentframe == trg2._totalframes && trg2._alpha) {
              trg.done = true;
            } else {
              trg2.nextFrame();
            }
            trg.sh._visible = false;
          }
        }
        e = 0;
        while (e < ball.length) {
          trg = ball[e];
          if (trg.d.done or trg.done or trg.s <= -10) {
            if (trg.s == 4) {
              if (_root.so.data.bomb > 100) {
                _root.SecretUnlocked[35] = true;
              }
            }
            if (trg.s == 30) {
              --boils;
            }
            ball.splice(e, 1);
            removeMovieClip(trg);
            trg.swapDepths(87);
          }
          ++e;
        }
        e = 0;
        while (e < ball.length) {
          trg = ball[e];
          trg.gh = false;
          ++e;
        }
        topz(3);
        grid.fillRect(grid.rectangle, 0);
        grid2.fillRect(grid2.rectangle, 0);
        tests.fillRect(tests.rectangle, 0);
        e = 0;
        bollocks = [];
        bollocks2 = [];
        while (e < ball.length) {
          trg = ball[e];
          if (trg == player) {
            ea = e;
          }
          ++e;
          if (trg.s > 3) {
            if ((trg.pbh or trg.outway) && trg.bh && !trg.dones) {
              f1 = gridp(trg.xp, trg.yp, -0.5, -0.5);
              gridput2([int(f1[0] + gridmax), int(f1[1])], e);
              gridput2([int(f1[0] + gridmax), int(f1[1] + 1)], e);
              gridput2([int(f1[0]), int(f1[1])], e);
              gridput2([int(f1[0]), int(f1[1] + 1)], e);
            } else {
              if (trg.ph && trg.bh && !trg.dones) {
                bollocks.push(e - 1);
              } else {
                if (trg.bh && !trg.dones) {
                  f1 = gridp(trg.xp, trg.yp, -0.5, -0.5);
                  gridput([int(f1[0] + gridmax), int(f1[1])], e);
                  gridput([int(f1[0] + gridmax), int(f1[1] + 1)], e);
                  gridput([int(f1[0]), int(f1[1])], e);
                  gridput([int(f1[0]), int(f1[1] + 1)], e);
                }
              }
            }
          }
        }
        i = 1;
        while (i < 300) {
          tests.setPixel(i, i, 1);
          ++i;
        }
        gxee = gxe * gridmax;
        i = 1;
        while (i < gxee) {
          o = 1;
          while (o < gye) {
            z = 0;
            for (;;) {
              if (!(z < gridmax && grid.getPixel(i + z, o) != 0)) break;
              e = grid.getPixel(i + z, o) - 1;
              c = z + 1;
              for (;;) {
                if (!(c < gridmax && grid.getPixel(i + c, o) != 0)) break;
                a = grid.getPixel(i + c, o) - 1;
                ballhit(e, a);
                ++c;
              }
              ++z;
            }
            ++o;
          }
          i += gridmax;
        }
        bollocks3 = [];
        for (e in ball) {
          trg = ball[e];
          if (trg.bh && !trg.outway) {
            if (trg.s < 5 or trg.s == 44 or trg.s == 28) {
              f1 = gridp(trg.xp, trg.yp);
              i = f1[0];
              o = f1[1];
              z = 0;
              for (;;) {
                if (!(z < gridmax && grid2.getPixel(i + z, o) != 0)) break;
                a = grid2.getPixel(i + z, o) - 1;
                ballhit(e, a);
                ++z;
              }
              if (trg.s < 5) {
                z = 0;
                for (;;) {
                  if (!(z < gridmax && grid.getPixel(i + z, o) != 0)) break;
                  a = grid.getPixel(i + z, o) - 1;
                  ballhit(e, a);
                  ++z;
                }
              }
            }
          }
        }
        for (i in bollocks) {
          a = bollocks[i];
          e = ea;
          ballhit(e, a);
          for (z in flys) {
            e = flys[z];
            ballhit(e, a);
          }
        }
        tip(3);
        if (flys.length > 2) {
          fll = 0.6666666666666666;
        } else {
          fll = 1;
        }
        flys = [];
        for (e in ball) {
          trg = ball[e];
          trg.xbew += trg.xb;
          trg.ybew += trg.yb;
          trg.rr = 0;
          trg.yb = 0;
          trg.xb = 0;
        }
        topz(4);
        for (e in ball) {
          trg = ball[e];
          if (!trg.ggh && !trg.dones) {
            f1 = trg.s > 2;
            if (trg == player or trg.s == 23 or trg.s == 55 or trg.s == 32 or trg.s == 44) {
              f1 = !enfcheckx(trg.xp, trg.yp, 320, 280, 1000) or hhorse > 0;
            }
            if (trg.s == 84) {
              trg.xp = Math.min(580, Math.max(60, trg.xp));
            } else {
              if (trg.s < 67 && trg.s > 62 or trg.s == 83) {
                trg.yp = Math.min(410, Math.max(170, trg.yp));
              } else {
                if (trg.flyai) {
                  trg.xp = Math.min(580, Math.max(60, trg.xp));
                  trg.yp = Math.min(410, Math.max(180, trg.yp));
                } else {
                  if (f1 && !trg.sic && !trg.horse && trg.s != 9 && !(trg.s >= 63 && trg.s <= 66)) {
                    trg.xp = Math.min(580, Math.max(60, trg.xp));
                    trg.yp = Math.min(417, Math.max(145, trg.yp));
                    if (trg == player) {
                      if (trg.xp == 580 or trg.xp == 60 or trg.xp == 417 or trg.xp == 145) {
                        if (horse < 90) {
                          horse = undefined;
                          trg.xbew *= 0.6;
                          trg.ybew *= 0.6;
                        }
                        f1 = ingrid(trg.xp, trg.yp);
                        if (levz[f1] > 1 && hhorse <= 0) {
                          turdb = f1;
                        }
                      }
                    }
                  }
                }
              }
            }
            if (trg == player) {
              if (turdb) {
                outgrid(turdb);
                if (enfcheck(xenf, yenf, trg.xp, trg.yp, 35)) {
                  turdz = levz[turdb];
                  levz[turdb] = 0;
                } else {
                  turdb = undefined;
                }
              }
            }
            f1 = trg.xp;
            f2 = trg.yp;
            f6 = 0;
            f5 = 0;
            siz = sizes[trg.s] + 2;
            v1 = trg.s;
            if (trg == player) {
              if (ladder != undefined) {
                if (levz[ladder] == 3) {
                  levz[ladder] = 0;
                }
              }
            }
            if (trg.shot) {
              if (trg._alpha > 50 && trg.sss != 84 && !trg.knife) {
                if (mhity(f1, f2)) {
                  mhix();
                } else {
                  if (levz[f33] == 0.99) {
                    if (webs[f33] && !trg.slowed) {
                      trg.slowed = true;
                      trg.xbew *= 0.64;
                      trg.ybew *= 0.64;
                    }
                  }
                }
              } else {
                if (random(10) == 0 or trg.knife) {
                  killshit(ingrid(trg.xp, trg.yp));
                }
              }
            } else {
              if (trg.flyby == 2) {
                mhix();
              } else {
                if (trg.flyby) {
                  f3 = false;
                  for (i in hardx[v1]) {
                    f3 = !f3;
                    if (f3) {
                      if (mhitx(f1 + hardx[v1][i], f2 + hardy[v1][i])) {
                        f5 += hardx[v1][i];
                        f6 += hardy[v1][i];
                      }
                    }
                  }
                  f3 = true;
                  if (Math.abs(f5) > 0 or Math.abs(f6) > 0 or trg.gh) {
                    for (i in hardx[v1]) {
                      f3 = !f3;
                      if (f3) {
                        if (mhitx(f1 + hardx[v1][i], f2 + hardy[v1][i])) {
                          f5 += hardx[v1][i];
                          f6 += hardy[v1][i];
                        }
                      }
                    }
                  }
                } else {
                  f3 = false;
                  for (i in hardx[v1]) {
                    f3 = !f3;
                    if (f3) {
                      if (mhit(f1 + hardx[v1][i], f2 + hardy[v1][i])) {
                        f5 += hardx[v1][i];
                        f6 += hardy[v1][i];
                      }
                    }
                  }
                  f3 = true;
                  if (Math.abs(f5) > 0 or Math.abs(f6) > 0 or trg.gh) {
                    for (i in hardx[v1]) {
                      f3 = !f3;
                      if (f3) {
                        if (mhit(f1 + hardx[v1][i], f2 + hardy[v1][i])) {
                          f5 += hardx[v1][i];
                          f6 += hardy[v1][i];
                        }
                      }
                    }
                  }
                }
              }
            }
            if (Math.abs(f5) > 0 or Math.abs(f6) > 0) {
              if (trg.s == 9) {
                trg.dones = true;
              }
              if (trg == player && fra > 20) {
                if (horse < 90) {
                  horse = undefined;
                  trg.xbew *= 0.6;
                  trg.ybew *= 0.6;
                }
                f1 = f6 * trg.ybew + f5 * trg.xbew;
                trg.xbew *= 0.88;
                trg.ybew *= 0.88;
                if (f1 > 0 or lastf1 > fra) {
                  if (f1 > 0) {
                    lastf1 = fra + 4;
                  }
                  trg.ghhh = true;
                  if (lastf2 <= fra) {
                    lastf2 = fra + 10;
                    if (Math.abs(f5) > Math.abs(f6)) {
                      lastxx = 0;
                      lastxy = 1;
                    } else {
                      lastxy = 0;
                      lastxx = 1;
                    }
                  }
                }
              }
              if (trg.s == 2 && !trg.dones) {
                trg.dones = true;
                v2 = 10 / enfget(trg.xbew, trg.ybew);
                v2 = ingrid(trg.xp + trg.xbew * v2, trg.yp + trg.ybew * v2);
                v1 = trg.dmg > 5;
                if (!killshit(v2, v1)) {
                  if (!killshit(ingrid(trg.xp + 10, trg.yp), v1)) {
                    if (!killshit(ingrid(trg.xp, trg.yp + 10), v1)) {
                      if (!killshit(ingrid(trg.xp - 10, trg.yp), v1)) {
                        killshit(ingrid(trg.xp, trg.yp - 10, v1));
                      }
                    }
                  }
                }
              }
              roty = sizes[trg.s] * Math.PI / 180;
              f7 = Math.sqrt(f5 * f5 + f6 * f6);
              f5 /= f7;
              f6 /= f7;
              if (trg.rotn != undefined) {
                trg.roty = (Math.atan(-f5 / f6) / Math.PI) * 180;
                if (f6 >= 0) {
                  trg.roty += 180;
                }
                trg.rotn = 3;
              }
              f8 = -f5 * trg.xbew - f6 * trg.ybew;
              if (f8 < 0) {
                ++trg.rr;
                trg.gh = true;
                if (trg.s == 99 && trg.fraz <= fra) {
                  trg.fraz = fra + 5;
                  _root.soundy('Death_Burst_Large_1.mp', f8 * 5);
                }
                f9 = f8 * 1.8 - 0.1;
                if (f9 < -10) {
                  soundy('mh');
                }
                if (trg.s == 99) {
                  f9 *= 1.4;
                }
                trg.xbew += f5 * f9;
                trg.ybew += f6 * f9;
                siz = Math.sqrt(trg.xbew * trg.xbew + trg.ybew * trg.ybew);
                siz2 = sizes[trg.s];
                if (siz > 0 && f8 < 0) {
                  f1 = trg.xp;
                  f2 = trg.yp;
                  if (trg.shot) {
                    if (trg.s == 14 or trg.s == 13) {
                      siz2 = 5;
                    }
                    v2 = siz2 - 10;
                    for (;;) {
                      if (!(!mhity(f1 + f5 * v2, f2 + f6 * v2) && v2 < siz2 + 10)) break;
                      v2 += 4;
                    }
                    v2 -= 4;
                    for (;;) {
                      if (!(!mhity(f1 + f5 * v2, f2 + f6 * v2) && v2 < siz2 + 10)) break;
                      v2 += 0.5;
                    }
                  } else {
                    if (trg.flyby) {
                      v2 = siz2 - 10;
                      for (;;) {
                        if (!(!mhitx(f1 + f5 * v2, f2 + f6 * v2) && v2 < siz2 + 10)) break;
                        v2 += 4;
                      }
                      v2 -= 4;
                      for (;;) {
                        if (!(!mhitx(f1 + f5 * v2, f2 + f6 * v2) && v2 < siz2 + 10)) break;
                        v2 += 0.5;
                      }
                    } else {
                      v2 = siz2 - 10;
                      for (;;) {
                        if (!(!mhit(f1 + f5 * v2, f2 + f6 * v2) && v2 < siz2 + 10)) break;
                        v2 += 4;
                      }
                      v2 -= 4;
                      for (;;) {
                        if (!(!mhit(f1 + f5 * v2, f2 + f6 * v2) && v2 < siz2 + 10)) break;
                        v2 += 0.5;
                      }
                    }
                  }
                  v2 -= siz2;
                  if (v2 > 0) {
                    v2 = 0;
                  } else {
                    v2 *= Math.max(0.2 - v2 * 0.05, 1);
                  }
                  trg.xp += f5 * v2;
                  trg.yp += f6 * v2;
                  f8 = -f8 / siz;
                  f8 = 1 - f8 * 0.5;
                  trg.xbew *= f8;
                  trg.ybew *= f8;
                }
              }
            }
            if (turdz) {
              levz[turdb] = turdz;
              turdz = undefined;
            }
            if (trg.rr > 0) {
              trg.xbew += trg.xb / trg.rr;
              trg.ybew += trg.yb / trg.rr;
            }
            if (trg == player) {
              if (ladder != undefined) {
                if (levz[ladder] == 0) {
                  levz[ladder] = 3;
                }
              }
            }
          }
        }
        e = 0;
        while (e < ball.length) {
          trg = ball[e];
          if (trg.laser) {
            trg2 = trg.d.l;
            if (Math.abs(trg.xpp) > Math.abs(trg.ypp)) {
              f1 = lass;
            } else {
              f1 = lass;
            }
            trg2._yscale = f1;
            trg2._xscale = laserDamage * 30;
          }
          trg._x = trg.xp;
          trg._y = trg.yp;
          if (trg.s == 19) {
            if (trg.dx) {
              trg._x -= trg.dx;
            }
          }
          if (trg.s == 19 && !altboss) {
          } else {
            if (trg.s == 26.5) {
            }
            if (trg.worm) {
              if (trg.d._y > 10) {
                trg2 = worm[1];
                trg._y = Math.min(trg._y, trg2.yppp);
              }
            }
            if (trg.s == 2) {
              trgdy(!trg.piss && !haveEffect[149]);
            } else {
              if (trg.s == 7 or trg.s == 8 or trg.s == 9) {
                trgdy();
              }
            }
            if (!trg.nod) {
              trg.dpppp = Math.max(e, Math.round(trg.yp) * 100 + 10030 + e);
              if (trg.s == 28) {
                trg.dpppp += 2500 - trg.mag * 1000;
              }
              if (trg.s == 5 && trg.d._currentframe == 9) {
                trg.dpppp -= 2500;
              }
              if (trg.s == 26.5) {
                trg.dpppp += 2500;
              }
              if (trg.worm) {
                if (trg.worm == 7) {
                  trg.dpppp += 1000;
                } else {
                  trg.dpppp -= Math.max(-30, trg.d._y) * 200;
                }
              }
              if (trg.s == 1 && trg.dones) {
                trg.dpppp += 100000000;
              }
              if (trg.flyai && gurdy) {
                trg.dpppp += 6000;
              }
              trg.swapDepths(trg.dpppp);
            }
            if (trg.col) {
              f1 = trg.col;
              if (trg.s == 5 && trg.d._currentframe == 7) {
                f1 = pillColor(f1);
              }
              trg.d.d.d.d.d.p.gotoAndStop(f1);
              trg.d.d.d.d.p.gotoAndStop(f1);
              trg.d.d.d.p.gotoAndStop(f1);
              trg.d.d.p.gotoAndStop(f1);
            }
            if (trg.s == 5) {
              if (trg.d.d._currentframe > 35 && trg.d.d._currentframe < 41) {
                if (trg.col == 31) {
                  f1 = 2;
                } else {
                  f1 = 1;
                }
                trg2 = trg.d.d.d;
                trg2.p.gotoAndStop(f1);
                trg2.p0.gotoAndStop(f1);
                trg2.p1.gotoAndStop(f1);
                trg2.p2.gotoAndStop(f1);
                trg2.p3.gotoAndStop(f1);
                trg2.p4.gotoAndStop(f1);
              }
            }
          }
          ++e;
        }
        tip(4);
      }

      function emo(f1) {
        if (f1) {
          if (emosound) {
            _root.soundy('thumbs down.wav');
          }
          player.d.gotoAndStop(10);
        } else {
          if (emosound) {
            _root.soundy('thumbsup.wav');
          }
          player.d.gotoAndStop(9);
        }
      }

      function lsou() {
        if (trg.ris + 27 <= fra) {
          if (trg.s == 84) {
            _root.soundy('hand lasers.mp');
          } else {
            if (trg.s == 1 or trg.s == 43 or trg.s == 49) {
              _root.soundy('Blood_Laser_Large.mp');
            } else {
              if (trg.s == 60) {
                _root.soundy('RedLightning_Zap_' + random(3) + '.mp');
              } else {
                _root.soundy('Blood_Laser' + random(2) + '.mp');
              }
            }
          }
        }
        trg.ris = fra;
      }

      function lasershowx(f1) {
        lsou();
        xenf = Math.cos(f1);
        yenf = Math.sin(f1);
        for (a in ball) {
          trg2 = ball[a];
          if (trg2.s != trg.s && !trg2.dones && (trg2.bh or trg2.s == 19) && trg2.s != 78 && !trg2.shot) {
            f4 = trg.xp - trg2.xp;
            f5 = trg.yp - trg2.yp;
            f2 = linearcut(f4, f5, xenf, yenf, -yenf, xenf);
            if (Math.abs(f2) < sizes[trg2.s] + 5) {
              if (linearcut(f4, f5, -yenf, xenf, xenf, yenf) < 0) {
                if (trg2 == player) {
                  playerhurt(1, trg.s);
                } else {
                  if (trg == player or !trg2.bosser) {
                    hurt(trg2, 22);
                  }
                }
              }
            }
          }
        }
      }

      function lasershow(trg, f50) {
        if (!f50) {
          lsou();
        }
        if ((fra + trg.e) % 2 == 0 or trg == player && haveEffect[118] or f50) {
          if (f50) {
            f1 = trg.xp;
            f2 = trg.yp;
            lass = 700;
            i = 1;
            while (i < 700) {
              f1 += trg.xpp * 10;
              f2 += trg.ypp * 10;
              f3 = ingrid(f1, f2);
              if (levz[f3] >= 1 && levz[f3] != 3 && (!haveEffect[115] or !haveEffect[68]) or f2 < 140 or f2 > 440 or f1 > 615 or f1 < 40) {
                lass = i;
                i = 1000;
              }
              i += 10;
            }
            lasx = trg.xp;
            lasy = trg.yp;
          }
          if (f50 != 2) {
            laserDamage = baseDamage();
            if (haveEffect[2]) {
              laserDamage *= 3;
            }
            if (haveEffect[132]) {
              laserDamage += 2;
            }
            if (brim) {
              lass = 10000;
              laserDamage *= 3;
              if (haveEffect[69]) {
                v111 = Math.max(0.1, Math.min(1, (fra - lchaf) / 60));
                laserDamage *= v111;
              }
            }
            _root.tearDamage = laserDamage;
          }
          if (f50 == 5) {
            laserDamage *= secol * 0.2;
          }
          for (a in ball) {
            trg2 = ball[a];
            if (trg2.s != trg.s && (trg.s != 3 or trg2 != player) && !trg2.dones && trg2.bh && !trg2.shot) {
              if (hps[trg2.s] > 0) {
                f1 = false;
                xenf = trg.xp - trg2.xp;
                yenf = trg.yp - trg2.yp;
                if (f50) {
                  f2 = 5;
                } else {
                  f2 = 25;
                }
                if (trg2 == player) {
                  f2 = 10;
                }
                f2 += sizes[trg2.s];
                if (Math.abs(trg.xpp) > Math.abs(trg.ypp)) {
                  if (Math.abs(yenf) < f2) {
                    if (xenf * trg.xpp < 0) {
                      f1 = true;
                    }
                  }
                } else {
                  if (Math.abs(xenf) < f2) {
                    if (yenf * trg.ypp < 0) {
                      f1 = true;
                    }
                  }
                }
                if (f1) {
                  if (trg2 == player) {
                    playerhurt(0.5, trg.s);
                  } else {
                    if (f50 or !f50 && trg == player && haveEffect[118]) {
                      if (enfget(xenf, yenf) - 20 < lass) {
                        hurt(trg2, laserDamage);
                        spidcol(trg2);
                      }
                    } else {
                      if (trg.s != 39 && (trg2.s != 84 or trg == player)) {
                        hurt(trg2, 22);
                      }
                    }
                  }
                }
              }
            }
          }
          f1 = 1000;
          if (f50) {
            f1 = lass + 10;
          }
          a = 0;
          while (a < f1) {
            killshit(ingrid(trg.xp + trg.xpp * a, trg.yp + trg.ypp * a), f50 && laserDamage > 5);
            a += 10;
          }
        }
      }

      function laps() {
        keyhole = false;
        if (keypoww > 0) {
          keypoww -= 0.2;
        }
        if (_root.keys > 0 or _root.goldenKey or haveEffect[60] or demon > 0 or _root.coins > 0 or unic > 0 or _root.notchedAxe) {
          f1 = roxx / enfget(player.xbew, player.ybew);
          f3 = ingrid(player.xp + player.xbew * f1, player.yp + player.ybew * f1);
          outgrid(f3);
          trg.s = 4;
          f10 = false;
          if (levz[f3] == 1 && (demon > 0 or _root.notchedAxe)) {
            bloww(f3, trg.xbew, trg.ybew);
            f10 = true;
          } else {
            if (demon > 0 or unic > 0 or _root.notchedAxe) {
              if (killshit(f3, demon > 0 or _root.notchedAxe)) {
                if (_root.notchedAxe) {
                  killshit(f3, true);
                  killshit(f3, true);
                }
                f10 = true;
              }
            }
          }
          if (_root.notchedAxe && f10) {
            _root.notchedAxe = false;
            _root.itemCharges = 0;
            player.d.gotoAndStop(11);
            player.it = 147;
            player.d.d.d.it.d.gotoAndStop(player.it);
            player.d.d.d.it.d.p.gotoAndStop(player.pillItem);
          }
          trg.s = 1;
          if (_root.keys > 0 or _root.goldenKey or _root.coins > 0) {
            keyhole = f3;
          }
          if (levz[f3] == 4 && (_root.goldenKey or _root.keys > 0)) {
            if (f3 != keypow) {
              keypow = f3;
              keypoww = 0;
            } else {
              if (keypoww++ > 2.8 && !player.flyby) {
                _root.soundy('Unlock00.wav', 100);
                if (!_root.goldenKey) {
                  --_root.keys;
                }
                levz[f3] = 1.01;
                killshit(f3);
                _root.soundy('metal_blockbreak' + random(2) + '.wav', 100);
              }
            }
          }
          if (levz[f3] == 3 && haveEffect[60]) {
            if (ladder != ingrid(player.xp, player.yp)) {
              if (Math.abs(trg.xbew) < Math.abs(trg.ybew)) {
                if (f3 != alad) {
                  if (trg.ybew < 0) {
                    lads._rotation = 0;
                  } else {
                    lads._rotation = 180;
                  }
                }
                if (levz[f3 + rowz] == 3 or levz[f3 - rowz] == 3) {
                  f3 = 0;
                }
              } else {
                if (f3 != alad) {
                  if (trg.xbew > 0) {
                    lads._rotation = 90;
                  } else {
                    lads._rotation = -90;
                  }
                }
                if (levz[f3 + 1] == 3 or levz[f3 - 1] == 3) {
                  f3 = 0;
                }
              }
              if (f3 > 0) {
                ladder = f3;
                alad = ladder;
                outgrid(ladder);
                lads._x = xenf;
                lads._y = yenf;
                lads._visible = true;
              }
            }
          }
        }
        if (ladder != undefined) {
          outgrid(ladder);
          if (!enfcheck(xenf, yenf, player.xp, player.yp, 100)) {
            ladder = undefined;
            lads._x = -10000;
            lads._visible = false;
          } else {
            outgrid(ladder);
            lads._x = xenf;
            lads._y = yenf;
            lads._visible = true;
          }
        }
      }

      function roll(f1) {
        if (f1) {
          roller = f1 - 1;
        }
        --roller;
        return random(roller + 1) == 0;
      }

      function tarotText(f1, f3) {
        var v1 = ['X Wheel of fortune', 'XV The Devil', 'XIII Death', 'XI Strength', '0 The Fool', 'I The Magician', 'IX The hermit', 'XVIII The Moon', 'XII The hanged Man', 'XX Judgement', 'VII The Chariot', 'VI The Lovers', 'XXI The World', 'VIII Justice', 'XVI Temperance', 'IV The Emperor', 'XVI The Tower', 'V The Hierophant', 'II The High Priestess', 'III The Empress', 'XIX The Sun', 'XVII The Stars'];
        v1[63] = '2 of Spades';
        v1[64] = '2 of Clubs';
        v1[65] = '2 of Hearts';
        v1[66] = '2 of Diamonds';
        v1[67] = 'The Joker';
        v1 = v1[f1 - 7];
        if (!f3) {
          displayBannerMessage(v1);
        } else {
          return v1;
        }
      }

      function goodpill() {
        _root.soundy('Powerup_spewer.wav', 100);
      }

      function fart() {
        var v2 = create(player.xp, player.yp, 0, 0, 0, 0, 4);
        v2.dones = true;
        v2._yscale = 70;
        v2._xscale = 70;
        v2.d.gotoAndStop(5);
        v2.fart = true;
        v2.s = 4.5;
        v2.dfr = true;
        showit = false;
        for (z in ball) {
          v2 = ball[z];
          siz = 85 + sizes[Math.round(v2.s)];
          enf = enfcheck(player.xp, player.yp, v2.xp, v2.yp, siz);
          if (enf < siz && !v2.dones && v2.s > 9 && v2.bh && !v2.shot) {
            v2.poisonDuration = 200;
            v2.poisonDamage = 3.5;
            hurt(v2, 5);
          }
        }
        _root.soundy('fart.mp');
      }

      function horss(f1) {
        if (horse == 100 or hfff == fra) {
          if (f1) {
            xenf = -xenf;
            yenf = -yenf;
          }
          if (xenf != 0 or yenf != 0) {
            horsx = xenf;
            horsy = yenf;
            if (xenf != 0 && yenf != 0) {
              if (Math.abs(trg.xbew) > Math.abs(trg.ybew)) {
                horsy = 0;
              } else {
                horsx = 0;
              }
            }
            horse = 99;
            hfff = fra;
          }
          if (f1) {
            xenf = -xenf;
            yenf = -yenf;
          }
        }
      }

      function identifyPill() {
        badPillsAvailable = !haveEffect[46] && !haveEffect[75];
        f1 = _root.pillEffects[_root.pillItem];
        while (f1 == undefined) {
          if (f1 == undefined or f1 == 3 && haveEffect[75] or f1 == 6 && (!badPillsAvailable or player.hp < 1)) {
            if ((player.hp < player.mhp or _root.characterID == 4 && _root.armor < 3) && random(10) == 0) {
              f1 = 1; //Full Health
            } else {
              if (random(13) == 0) {
                f1 = 12; //Bad Gas
              } else {
                if (random(17) == 0) {
                  f1 = 13; //Friends Till The End!
                } else {
                  if (random(17) == 0) {
                    f1 = 14 + random(2) * 0.2; //Luck Up/Down
                  } else {
                    if (random(15) == 0 && !haveEffect[75]) {
                      f1 = 2; //I Found Pills
                    } else {
                      if (random(10) == 0 && !haveEffect) { //BROKEN
                        f1 = 3; //Explosive Diarrhea
                      } else {
                        if (random(10) == 0) {
                          f1 = 4; //Balls of Steel
                        } else {
                          if (random(20) == 0) {
                            f1 = 5; //Pretty Fly
                          } else {
                            if (random(9) == 0 && player.hp + _root.armor > 1 && badPillsAvailable) {
                              f1 = 6; //Bad Trip
                            } else {
                              if (random(7) == 0) {
                                f1 = 7 + random(2) * 0.2; //Health Up/Down
                              } else {
                                if (random(6) == 0 && (_root.bombs > 0 or _root.keys > 0)) {
                                  f1 = 8; //Bombs Are Key
                                } else {
                                  if (random(5) == 0 or random(4) == 0 && haveEffect) { //???
                                    f1 = 9 + random(2) * 0.2; //Tears Up/Down
                                  } else {
                                    if (random(3) == 0) {
                                      f1 = 10 + random(2) * 0.2; //Range Up/Down
                                    } else {
                                      if (random(3) == 0 or haveEffect[75]) {
                                        f1 = 11 + random(2) * 0.2; //Speed Up/Down
                                      } else {
                                        f1 = 126; //Telepills
                                      }
                                    }
                                  }
                                }
                              }
                            }
                          }
                        }
                      }
                    }
                  }
                }
              }
            }
            for (z in _root.pillEffects) {
              if (f1 == _root.pillEffects[z]) {
                f1 = undefined;
              }
            }
            _root.pillEffects[_root.pillItem] = f1;
          }
        }
        f1 = Math.round(_root.pillEffects[_root.pillItem]);
        if (f1 != _root.pillEffects[_root.pillItem]) {
          f2 = true;
        } else {
          f2 = false;
        }
        if (!badPillsAvailable) {
          f2 = true;
        }
      }

      function cardDoubler(f1) {
        return Math.max(f1 * 2, 2);
      }

      function playc() {
        trg = player;
        f2 = trg.xp;
        f3 = trg.yp;
        if (decer.s == 4) {
          f2 = decer.xp;
          f3 = decer.yp;
        }
        f1 = levz[ingrid(f2, f3)];
        if (f1 < 1) {
          playx = f2;
          playy = f3;
        }
        if (fra < 10 && (player.hp < 1 && _root.characterID != 4 or _root.armor < 1 && _root.characterID == 4)) {
          if (_root.characterID == 5) {
            splater(trg.xp, trg.yp, random(10) + 1, 0.3 + Math.random() * 0.5);
          } else {
            splater(trg.xp, trg.yp, random(10) + 20, 0.3 + Math.random() * 0.5);
          }
        }
        if (loseCoins) {
          loseCoins = false;
          if (_root.coins > 0) {
            --_root.coins;
            f3 = Math.min(_root.coins, random(3) + 1);
            z = 0;
            while (z < f3) {
              --_root.coins;
              f4 = random(5) + 2;
              trg2 = create(player.xp, player.yp, 0, crand(f4), crand(f4), 0, 5.02);
              trg2.col = 1;
              ++z;
            }
          }
        }
        if (missileTimer-- > 0) {
          drop.d.gotoAndStop(Math.max(1, Math.round(100 - missileTimer)));
          if (missileTimer == 2) {
            bomf.push([drop.xp, drop.yp, 4]);
            drop.done = true;
          }
          if (haveEffect[168]) {
            player.fire = 10;
          }
        }
        trg2 = player;
        if (random(4) == 0 && haveEffect[189]) {
          splater(trg2.xp, trg2.yp + 5, 1 + random(10), Math.random() * 0.5 + 0.3);
        }
        for (a in ball) {
          trg = ball[a];
          siz = 270;
          if (trg.s == 5) {
            if (haveEffect[53] or trg.d._currentframe == 4 && trg.col == 5) {
              if (!trg.empty && trg.d._currentframe <= 4 && trg.bh && (trg.d._currentframe != 1 or trg.col == 3 or player.hp < player.mhp)) {
                if (enfcheck(trg2.xp, trg2.yp, trg.xp, trg.yp, siz)) {
                  enf = 0.5 / enf;
                  if (trg.d._currentframe == 4 && trg.col == 5) {
                    enf *= 3;
                  }
                  trg.xbew += xenf * enf;
                  trg.ybew += yenf * enf;
                  trg.xbew *= 0.8;
                  trg.ybew *= 0.8;
                  trg.ggh = true;
                }
              } else {
                trg.ggh = false;
              }
            }
          }
        }
        if (scare > 0) {
          for (a in ball) {
            trg = ball[a];
            siz = 270;
            if (trg.s > 9 && (!trg.flyai or trg.s == 18)) {
              trg.xp = Math.min(580, Math.max(60, trg.xp));
              trg.yp = Math.min(410, Math.max(170, trg.yp));
              if (enfcheck(trg2.xp, trg2.yp, trg.xp, trg.yp, siz)) {
                enf = ((siz - enf) / enf) * 0.007;
                trg.xbew -= xenf * enf;
                trg.ybew -= yenf * enf;
                trg.xbew *= 0.85;
                trg.ybew *= 0.85;
                if (trg.sf) {
                  sideflip(trg.xbew);
                }
                if (trg.wf) {
                  walkframe();
                }
              }
            }
          }
        } else {
          if (slow > 0 or sloww > 0) {
            for (a in ball) {
              trg = ball[a];
              if (trg.free) {
                colorit(trg, 1, 1, 1.3, 40, 40, 40);
              }
            }
          } else {
            if (freez > 0) {
              for (a in ball) {
                trg = ball[a];
                if (trg.free) {
                  trg.frezz = freez + 1;
                  colorit(trg, 0.22, 0.22, 0.22, 40, 40, 40);
                }
              }
            } else {
              if (freez == 0 or slow == 0 or sloww == 0) {
                for (a in ball) {
                  trg = ball[a];
                  if (trg.free) {
                    trg.free = undefined;
                    specialColoring(trg);
                  }
                }
              }
            }
          }
        }
        trg = player;
        if (playslow-- > 0) {
          trg.xbew *= 0.7;
          trg.ybew *= 0.7;
        }
        trg = player;
        trg = player;
        if (trg.dones) {
          unpause = false;
          trg.xbew *= 0.8;
          trg.ybew *= 0.8;
          colorPlayer();
        } else {
          f55 = 0;
          f44 = false;
          if (firecheck(player)) {
            if (f44) {
            } else {
              if (!relf) {
                playerhurt(0.5, 6);
              } else {
                if (relf == 2) {
                  playerhurt(1, 5);
                } else {
                  for (i in door) {
                    trg = door[i];
                    if (f55 == trg.blo) {
                      f55 = 1.1;
                    }
                  }
                  if (_root.lev == _root.sacrificeRoom && !_root.successSacrifice && lasth - fra < 0) {
                    if (random(5) == 0 or player.hp < 2 && _root.armor <= 0) {
                      _root.successSacrifice = true;
                      create(320, 340, 0, 0, 0, 0, 5.05 + random(2) * 0.01);
                    }
                  }
                  if (f55 == 1.1) {
                    playerhurt(0.5, 7);
                  } else {
                    playerhurt(1, 7);
                  }
                }
              }
            }
          }
          if (f44) {
            playslow = 4;
          }
          f1 = lasth - fra;
          _root.lasth = f1 > 6;
          if (f1 > 6 or unic > 0 && (!pacman or unic < 30)) {
            if (f1 % 3 == 0 or unic > 0) {
              if (f1 % 2 == 0) {
                colorPlayer(true);
              } else {
                colorPlayer();
              }
            }
          } else {
            colorPlayer();
          }
          for (e in door) {
            trg = door[e];
            if (trg._visible && player._visible && lastspin <= fra && !(hhorse > 0 && ashut > 0)) {
              v1 = enfcheck(trg.xp, trg.yp, player.xp, player.yp, 35);
              if (v1 < 25 && trg.nod && fra > 30) {
                if (shutdoor != 0) {
                  _root.beenlev[_root.lev] = false;
                }
                _root.door = e;
                if (e == 0 or e == 2) {
                  _root.playerx = 610 - trg._x * 0.9;
                  _root.playery = 280;
                } else {
                  _root.playerx = 320;
                  _root.playery = 530 - trg._y * 0.9;
                }
                invp();
                _root.old.fillRect(_root.old.rectangle, 0);
                _root.old.draw(this);
                _root.olda._x = 0;
                _root.olda._y = 0;
                _root.olda._visible = true;
                moveon();
                _root.lev = trg.gol;
                _root.gotoAndStop('reset');
              }
              if (!v1) {
                trg.nod = true;
              }
            }
          }
          trg = player;
          if (_root.bombnext or _root.notchedAxe) {
            if (trg.d._currentframe == 11) {
              if (trg.d.d.d._currentframe > 9) {
                trg.d.d.d.gotoAndStop(10);
              }
            } else {
              trg.d.gotoAndStop(11);
              if (_root.bombnext == 2) {
                trg.it = 164;
              } else {
                if (_root.notchedAxe) {
                  trg.it = 147;
                } else {
                  trg.it = 42;
                }
              }
            }
          }
          if (farter) {
            farter = false;
            fart();
          }
          spac = Key.isDown(32) or Key.isDown(90) && !_root.so.data.frog;
          if (spac) {
            if (_root.notchedAxe or _root.bombnext) {
              if (!nosp) {
                nosp = true;
                _root.notchedAxe = false;
                _root.bombnext = false;
              }
            }
          } else {
            nosp = false;
          }
          if (trg.d._currentframe >= 3) {
            if (!_root.bombnext) {
              trg.fire = 5;
            }
            trg.xbew *= 0.8;
            trg.ybew *= 0.8;
          } else {
            if (Key.isDown(17) or Key.isDown(16) or Key.isDown(69)) {
              bomb();
            }
            bomberfail -= 0.024;
            if (bomberfail > 0 && nextbo) {
              --bomberfail;
              lastbo = 0;
              bomb(2);
              nextbo = false;
            }
            if ((Key.isDown(81) && !_root.so.data.frog or Key.isDown(65) && _root.so.data.frog) && fra > 30 && _root.pillItem != undefined) {
              _root.hud.pilll.gotoAndStop(3);
              player.d.gotoAndStop(11);
              player.it = 43;
              player.d.d.d.it.d.gotoAndStop(player.it);
              player.d.d.d.it.d.p.gotoAndStop(pillColor(_root.pillItem));
              if (_root.pillItem >= 7) {
                tarotText(_root.pillItem);
                switch (_root.pillItem) {
                  case 70:		//2 of Spades
                    _root.keys = cardDoubler(_root.keys);
                    break;
                  case 71:		//2 of Clubs
                    _root.bombs = cardDoubler(_root.bombs);
                    break;
                  case 72:		//2 of Hearts
                    player.hp = cardDoubler(player.hp);
                    break;
                  case 73:		//2 of Diamonds
                    _root.coins = cardDoubler(_root.coins);
                    break;
                  case 74:		//The Joker
                    teleportTarget = 166;
                    teleport();
                    break;
                  case 28:		//The Stars
                    teleport();
                    teleportTarget = _root.boner;
                    _root.treasureRoomOpened = true;
                    break;
                  case 27:		//The Sun
                    _root.over.gotoAndStop(15);
                    player.hp = 1000;
                    haveEffect[54] = true;
                    haveEffect[21] = haveEffect[54];
                    _root.world = true;
                    mapd();
                    for (e in ball) {
                      trg2 = ball[e];
                      hurt(trg2, 100);
                    }
                    break;
                  case 26:		//The Empress
                    curs();
                    haveEffect[122] = 1.5;
                    break;
                  case 25:		//The High Priestess
                    f1 = 0;
                    f2 = 4;
                    for (z in ball) {
                      trg2 = ball[z];
                      if (trg2.s > 9 && trg2.s != 45 or trg2 == player) {
                        if (trg2.hp > f2 && trg2.satanPhase != 1 && trg2.satanPhase != 2) {
                          f2 = trg2.hp;
                          f1 = z;
                        }
                      }
                    }
                    trg3 = ball[f1];
                    trg2 = create(trg3.xp, trg3.yp, 0, 0, 0, 0, 45);
                    trg2.weap = true;
                    trg2.ggh = true;
                    trg2.d.gotoAndStop(20);
                    trg2.trg2 = trg3;
                    trg2.bh = false;
                    trg2.fra = -100;
                    trg2.specoz = undefined;
                    break;
                  case 20:		//Justice
                    spaw(player.xp, player.yp, 45, 5.01);
                    spaw(player.xp, player.yp, 45, 5.02);
                    spaw(player.xp, player.yp, 45, 5.03);
                    spaw(player.xp, player.yp, 45, 5.04);
                    break;
                  case 19:		//The World
                    haveEffect[54] = true;
                    haveEffect[21] = haveEffect[54];
                    _root.world = true;
                    mapd();
                    break;
                  case 18:		//The Lovers
                    f1 = 40;
                    trg2 = spaw(player.xp + f1, player.yp, 0, 5.01);
                    trg3 = spaw(player.xp - f1, player.yp, 0, 5.01);
                    trg2.col = 1;
                    trg3.col = 1;
                    break;
                  case 24:		//The Hierophant
                    f1 = 40;
                    trg2 = spaw(player.xp + f1, player.yp, 0, 5.01);
                    trg3 = spaw(player.xp - f1, player.yp, 0, 5.01);
                    trg2.col = 3;
                    trg3.col = 3;
                    break;
                  case 17:		//The Chariot
                    player.it = 77;
                    unic = 180;
                    _root.mmus = _root.soundy('isaacunicorn.mp', 100);
                    break;
                  case 23:		//The Tower
                    anarch = 30;
                    break;
                  case 21:		//Temperance
                    spaw(player.xp, player.yp, 45, 5.31);
                    _root.soundy('summonsound.wav', 120);
                    break;
                  case 22:		//The Empreror
                    teleport();
                    teleportTarget = _root.bossRoom;
                    break;
                  case 16:		//Judgement
                    spaw(player.xp, player.yp, 45, 5.32);
                    _root.soundy('summonsound.wav', 120);
                    break;
                  case 7:		//Wheel of Fortune
                    spaw(player.xp, player.yp, 45, 5.08);
                    _root.soundy('summonsound.wav', 120);
                    break;
                  case 8:		//The Devil
                    belial = true;
                    _root.over.gotoAndStop(2);
                    _root.soundy('Devil_Card.mp', 100);
                    break;
                  case 9:		//Death
                    _root.over.gotoAndStop(11);
                    _root.soundy('Death_Card.mp', 100);
                    for (e in ball) {
                      trg2 = ball[e];
                      hurt(trg2, 60);
                    }
                    ++_root.so.data.deathCardUses;
                    if (_root.so.data.deathCardUses > 4) {
                      _root.SecretUnlocked[48] = true;
                    }
                    break;
                  case 10:		//Strength
                    ++player.hp;
                    ++haveEffect[12];
                    break;
                  case 11:		//The Fool
                    teleport();
                    teleportTarget = 35;
                    break;
                  case 12:		//The Magician
                    ++haveEffect[3];
                    break;
                  case 13:		//The Hermit
                    teleport();
                    teleportTarget = _root.shopl;
                    _root.shopa = true;
                    break;
                  case 14:		//The Moon
                    teleport();
                    teleportTarget = _root.secretRoom;
                    break;
                  case 15:		//The Hanged Man
                    ++haveEffect[20];
                }
              } else {
                identifyPill();
                switch (Math.round(f1)) {
                  case 14:
                    if (f2) {
                      ++_root.luck;
                      displayCornerMessage('Luck Up');
                      goodpill();
                      emo();
                      pillTintPlayer(50, 100, 50);
                    } else {
                      displayCornerMessage('Luck Down');
                      --_root.luck;
                      emo(true);
                    }
                    break;
                  case 13:
                    blueFlies += 3;
                    displayCornerMessage('Friends till the end!');
                    break;
                  case 6:
                    if (player.hp + _root.armor > 1) {
                      lasth = 0;
                      playerhurt(1, 201);
                      displayCornerMessage('Bad Trip!');
                    } else {
                    case 1:
                      if (_root.characterID == 4) {
                        if (_root.armor < 3) {
                          _root.armor = 3;
                        }
                      } else {
                        if (player.mhp > 0) {
                          player.hp = player.mhp;
                        }
                      }
                      displayCornerMessage('Full Health');
                      goodpill();
                      emo();
                      break;
                    case 2:
                      if (random(2) == 0) {
                        hat(54);
                        displayBannerMessage('Puberty');
                      } else {
                        _root.headMode = 16;
                        displayBannerMessage('I found Pills');
                        displayCornerMessage('And ate them!');
                        _root.soundy('derp.mp');
                      }
                      break;
                    case 3:
                      bomberfail = 5.5;
                      displayCornerMessage('Oh no!');
                      emo(true);
                      _root.soundy('fart.mp');
                      break;
                    case 4:
                      _root.armor += 2;
                      displayCornerMessage('Balls of Steel');
                      goodpill();
                      emo();
                      break;
                    case 5:
                      _root.pickedUp[10] += 0.5;
                      haveEffect[10] = _root.pickedUp[10];
                      displayCornerMessage('Pretty Fly');
                      goodpill();
                      emo();
                      break;
                    case 7:
                      if (_root.characterID != 4) {
                        f13 = player.mhp;
                      } else {
                        f13 = _root.armor;
                      }
                      if (f13 <= 1 or f2) {
                        displayCornerMessage('Health Up');
                        if (_root.characterID == 4) {
                          ++_root.armor;
                        } else {
                          ++_root.pickedUp[15];
                        }
                        pillTintPlayer(100, 50, 50);
                        goodpill();
                        emo();
                      } else {
                        if (_root.characterID == 4) {
                          --_root.armor;
                        } else {
                          --_root.pickedUp[15];
                        }
                        displayCornerMessage('Health Down');
                        emo(true);
                      }
                      haveEffect[15] = _root.pickedUp[15];
                      break;
                    case 8:
                      f1 = _root.bombs;
                      _root.bombs = _root.keys;
                      _root.keys = f1;
                      displayCornerMessage('Bombs are Key');
                      emo();
                      break;
                    case 9:
                      if (f2) {
                        _root.pickedUp[32] += 0.5;
                        displayCornerMessage('Tears Up');
                        pillTintPlayer(80, 80, 100);
                        goodpill();
                        emo();
                      } else {
                        _root.pickedUp[32] -= 0.4;
                        displayCornerMessage('Tears Down');
                        emo(true);
                      }
                      haveEffect[32] = _root.pickedUp[32];
                      break;
                    case 10:
                      if (f2 or haveEffect[6] && _root.floorNum < 8) {
                        _root.pickedUp[31] += 0.5;
                        displayCornerMessage('Range Up');
                        pillTintPlayer(50, 100, 100);
                        emo();
                        goodpill();
                      } else {
                        _root.pickedUp[31] -= 0.4;
                        displayCornerMessage('Range Down');
                        emo(true);
                      }
                      haveEffect[31] = _root.pickedUp[31];
                      break;
                    case 11:
                      if (f2) {
                        ++_root.pickedUp[27];
                        displayCornerMessage('Speed Up');
                        pillTintPlayer(100, 100, 50);
                        goodpill();
                        emo();
                      } else {
                        _root.pickedUp[27] -= 0.8;
                        displayCornerMessage('Speed Down');
                        emo(true);
                      }
                      haveEffect[27] = _root.pickedUp[27];
                      break;
                    case 12:
                      fart();
                      displayCornerMessage('Bad Gas');
                      break;
                    case 126:
                      f1 = random(15);
                      if (_root.floorNum != 9) {
                        if (f1 == 0) {
                          teleportTarget = 169;
                        } else {
                          if (f1 == 0 && _root.floorNum != 1) {
                            teleportTarget = 166;
                          }
                        }
                      }
                      displayCornerMessage('TelePills');
                      teleport();
                    }
                }
              }
              player.pillItem = _root.pillItem;
              _root.pillItem = undefined;
            }
            if (spac && (fra > 30 or _root.spacebarItem == 90 && _root.lev != _root.bossRoom2 && _root.lev != _root.bossRoom && _root.lev != 35) && player._visible) {
              if (!nosp) {
                nosp = true;
                if (_root.spacebarItem > 0 && _root.itemCharges >= 1) {
                  doit = true;
                  showit = true;
                  pacman = false;
                  if (_root.spacebarItem == 84) {
                    scrollEffects = [2, 3, 5, 6, 7, 8, 9, 10, 12, 13, 16, 17, 18, 19, 25, 26, 37, 38, 43, 44, 45, 46, 53, 57, 62, 67];
                    if (scrollEffects.length > 0) {
                      scrollEffects = scrollEffects[random(scrollEffects.length)];
                      _root.spacebarItem = scrollEffects;
                      scrollEffects += spacebarIDToItemID(scrollEffects);
                      displayCornerMessage(_root.itemNames[scrollEffects]);
                    }
                    _root.over.gotoAndStop(14);
                    goper = true;
                  }
                  switch (_root.spacebarItem) {
                    case 152:	//Telepathy for Dummies
                      haveEffect[3] = 1;
                      break;
                    case 146:	//Blood Rights
                      donateBlood();
                      lasth = 0;
                      if (_root.floorNum < 7) {
                        donateBlood(true);
                      }
                      if (player.hp < 0.5) {
                        showit = false;
                      }
                      _root.soundy('Death_Card.mp', 100);
                      for (e in ball) {
                        trg2 = ball[e];
                        hurt(trg2, 40);
                      }
                      sacri = 20;
                      break;
                    case 120:	//Crack The Sky
                      anarch = 30;
                      analt = 2;
                      break;
                    case 124:	//The Candle
                      _root.bombnext = 2;
                      break;
                    case 135:	//Dad's Key
                      keyd = true;
                      break;
                    case 126:	//D20
                      for (e in ball) {
                        trg2 = ball[e];
                        if (trg2.s == 5) {
                          if (trg2.d._currentframe < 8) {
                            trg2.done = true;
                            f1 = 5.01 + random(6) * 0.01;
                            if (f1 == 5.06 && random(2) == 0) {
                              f1 = 5.01;
                            }
                            if (f1 == 5.05 && random(3) == 0) {
                              f1 = 5.02;
                            }
                            if (random(10) == 0) {
                              f1 = 5.03 + random(2) * 0.01;
                            }
                            if (random(15) == 0) {
                              f1 = 5.3;
                            }
                            if (random(15) == 0) {
                              f1 = 5.07;
                            }
                            if (random(20) == 0) {
                              f1 = 5.35;
                            }
                            create(trg2.xp, trg2.yp, 0, 0, 0, 0, f1);
                          }
                        }
                      }
                      break;
                    case 131:	//Spider Butt
                      _root.soundy('Death_Card.mp', 100);
                      for (e in ball) {
                        trg2 = ball[e];
                        hurt(trg2, 10);
                        spida(undefined, trg2);
                      }
                      break;
                    case 137:	//Portable Slot
                      if (_root.coins > 0 && portableSlot == undefined) {
                        --_root.coins;
                        portableSlot = 25;
                      } else {
                        showit = false;
                      }
                      break;
                    case 107:	//Notched Axe
                      _root.notchedAxe = !_root.notchedAxe;
                      doit = false;
                      showit = false;
                      break;
                    case 118:	//Crystal Ball
                      haveEffect[54] = true;
                      haveEffect[21] = haveEffect[54];
                      _root.world = true;
                      mapd();
                      if (random(2) == 0) {
                        spaw(trg.xp, trg.yp, 40, 5.3);
                      } else {
                        trg2 = spaw(trg.xp, trg.yp, 40, 5.01);
                        trg2.col = 3;
                      }
                      break;
                    case 105:	//Guppy's Head
                      blueFlies += 2 + random(3);
                      break;
                    case 96:	//Best Friend
                      decoy = 0;
                      break;
                    case 106:	//Prayer Card
                      giveEternalHeart();
                      break;
                    case 97:	//Remote Detonator
                      for (e in ball) {
                        trg = ball[e];
                        if (trg.s == 4) {
                          trg.d.gotoAndStop(3);
                          trg.dones = true;
                        }
                      }
                      break;
                    case 95:	//IV Bag
                      donateBlood();
                      f12 = Math.max(1, random(3));
                      if (haveEffect[75]) {
                        ++f12;
                      }
                      f11 = 0;
                      while (f11 < f12) {
                        spaw(trg.xp, trg.yp, 40, 5.02);
                        ++f11;
                      }
                      showit = player.hp > 0;
                      break;
                    case 93:	//Guppy's Paw
                      if (player.mhp > 0) {
                        _root.armor += 3;
                        --_root.pickedUp[22];
                        player.hp = Math.max(player.hp - 1, 0.5);
                        --haveEffect[22];
                        _root.soundy('Vamp_Gulp.mp');
                      } else {
                        showit = false;
                      }
                      break;
                    case 141:	//White Pony
                      anarch = 20;
                      analt = 3;
                    case 90:	//A Pony
                      showit = false;
                      horse = 100;
                      break;
                    case 83:	//Monster Manuel
                      _root.soundy('satan grow.mp', 70);
                      f1 = [8, 73, 10, 57, 67, 88, 95, 99, 100, 112, 113, 128];
                      for (e in f1) {
                        if (haveEffect[f1[e]]) {
                          f1.splice(e, 1);
                        }
                      }
                      if (f1.length > 0) {
                        f1 = f1[random(f1.length)];
                        haveEffect[f1] = 1;
                      }
                      if (f1 == 73) {
                        haveEffect[f1] = random(2) + 2;
                      }
                      displayCornerMessage(_root.itemNames[f1]);
                      _root.over.gotoAndStop(12);
                      break;
                    case 84: 	//Dead Sea Scrolls (see above)
                      break;
                    case 87:	//Forget Me Now
                      _root.beenlev[_root.lev] = false;
                      _root.shroom = 3;
                      _root.spacebarItem = 0;
                      _root.door = undefined;
                      _root.playerx = 320;
                      _root.playery = 400;
                      _root.getup = true;
                      --_root.floorNum;
                      if (_root.labyrinthCurse) {
                        --_root.floorNum;
                      }
                      newstart(false);
                      _root.gotoAndStop('reset');
                      break;
                    case 86:	//Razor Blade
                      razor += 2;
                      if (player.hp > 0.5 or _root.armor <= 0) {
                        f11 = _root.armor;
                        _root.armor = 0;
                        playerhurt(0.5, 202);
                        _root.armor = f11;
                      } else {
                        playerhurt(0.5, 202);
                      }
                      lasth = 0;
                      if (player.hp > 0.5 or _root.armor <= 0) {
                        f11 = _root.armor;
                        _root.armor = 0;
                        playerhurt(0.5, 202);
                        _root.armor = f11;
                      } else {
                        playerhurt(0.5, 202);
                      }
                      showit = false;
                      break;
                    case 71:	//The Bean
                      fart();
                      break;
                    case 67:	//The Pinking Shears
                      ++haveEffect[20];
                      bodd = true;
                      _root.soundy('bloodbank spawn1.wav', 300);
                      break;
                    case 65:	//The D6
                      for (a in ball) {
                        trg2 = ball[a];
                        if (trg2.s == 5 && trg2.it && !trg2.empty) {
                          trg2.it = GenerateItem();
                          if (trg2.d._currentframe == 10) {
                            trg2.d.d.gotoAndPlay(1);
                          }
                        }
                      }
                      break;
                    case 62:	//Mom's Bottle of Pills
                      givePillItem(4);
                      showit = false;
                      break;
                    case 57:	//The Book of Sin
                      f1 = [5.010000001, 5.010000003, 5.040000001, 5.03, 5.07, 5.3, 5.02];
                      f1 = f1[random(f1.length)];
                      spaw(trg.xp, trg.yp, 40, f1);
                      break;
                    case 38:	//The Book of Revelations
                      if (_root.canSpawnHorseman && _root.lev != _root.bossRoom && _root.floorNum < 8 && _root.floorNum != 6 && !_root.labyrinthCurse) {
                        _root.spawnHorseman = true;
                        _root.canSpawnHorseman = false;
                        f1 = Math.round(_root.floorNum / 2);
                        _root.bossID = f1 + 8;
                        if (random(10) == 0 && !_root.nohead) {
                          _root.nohead = true;
                          f1 = 5;
                          _root.bossID = 22;
                        }
                        _root.levz[_root.bossRoom] = 'h' + f1;
                      }
                      ++_root.armor;
                      break;
                    case 43:	//The Nail
                      demon = 200;
                      _root.soundy('Monster_Yell_A_0.mp');
                      ++_root.armor;
                      break;
                    case 44:	//We Need To Go Deeper!
                      if (_root.floorNum < 9) {
                        spaw(trg.xp, trg.yp, 0, 5.09);
                      } else {
                        showit = false;
                        doit = false;
                      }
                      break;
                    case 45:	//Deck of Cards
                      givePillItem(3);
                      showit = false;
                      break;
                    case 53:	//The Gamekid
                      _root.mmus = _root.soundy('isaacunicorn.mp', 100);
                      unic = 200;
                      pacman = true;
                      scare = 180;
                      for (z in ball) {
                        trg2 = ball[z];
                        trg2.uncol = fra + 2;
                      }
                      break;
                    case 46:	//Monstro's Tooth
                      f1 = 0;
                      f2 = 4;
                      for (z in ball) {
                        trg2 = ball[z];
                        if (trg2.s > 9 && trg2.s != 20) {
                          if (trg2.hp > f2) {
                            if (!enfcheck(trg2.xp, trg2.yp, player.xp, player.yp, 40)) {
                              f2 = trg2.hp;
                              f1 = z;
                            }
                          }
                        }
                      }
                      if (f1 > 0) {
                        trg3 = ball[f1];
                        trg2 = create(trg3.xp, trg3.yp, 0, 0, 0, 0, 20);
                        trg2.weap = true;
                        trg2.ggh = true;
                        trg2.d.gotoAndStop(3);
                        trg2.trg2 = trg3;
                        trg2.bh = false;
                        trg2.fra = -100;
                      } else {
                        showit = false;
                        doit = false;
                      }
                      break;
                    case 1:	//The Bible
                      if (_root.floorNum == 9 && _root.lev == _root.bossRoom) {
                        _root.armor = 0;
                        playerhurt(1000, 200);
                      } else {
                        if ((mom.length > 3 or momHeart != undefined) && !bibs && (_root.floorNum == 6 or _root.floorNum == 8) && _root.lev == _root.bossRoom) {
                          bibs = true;
                          momHeart.dones = true;
                          for (z in mom) {
                            mom[z].dones = true;
                            mom[z]._visible = false;
                          }
                          momkill();
                          _root.SecretUnlocked[34] = true;
                        }
                      }
                      bible = true;
                      _root.over.gotoAndStop(8);
                      _root.soundy('Book Page Turn 12.wav', 100);
                      break;
                    case 37:	//My Little Unicorn
                      unic = 180;
                      _root.mmus = _root.soundy('isaacunicorn.mp', 100);
                      break;
                    case 18:	//Book of Shadows
                      playsave = 300;
                      break;
                    case 16:	//Lemon Mishap
                      create(trg.xp, trg.yp, 0, 0, 0, 0, 33);
                      _root.soundy('BGascan_pour.wav', 100);
                      break;
                    case 2:		//The Book of Belial
                      belial = true;
                      _root.over.gotoAndStop(2);
                      _root.soundy('Devil_Card.mp', 100);
                      break;
                    case 3:		//The Necronomicon
                      _root.over.gotoAndStop(3);
                      _root.soundy('Death_Card.mp', 100);
                      for (e in ball) {
                        trg2 = ball[e];
                        hurt(trg2, 40);
                      }
                      break;
                    case 4:		//The Poop
                      showit = false;
                      f1 = ingrid(trg.xp, trg.yp);
                      outgrid(f1);
                      turd('breakblock', f1);
                      _root.soundy('fart.mp');
                      turdb = f1;
                      break;
                    case 11:
                      doit = false;
                      showit = false;
                      break;
                    case 10:	//Bob's Rotten Head
                      doit = false;
                      _root.bombnext = true;
                      break;
                    case 15:	//Doctor's Remote
                      if (missileTimer <= 0) {
                        missileTimer = 100;
                        drop = create(player.xp, player.yp, 0, 0, 0, 0, 37);
                      } else {
                        doit = false;
                      }
                      break;
                    case 7:		//Mom's Bra
                      _root.over.gotoAndStop(4);
                      freez = 220;
                      bra = true;
                      break;
                    case 9:		//Mom's Pad
                      _root.over.gotoAndStop(5);
                      scare = 180;
                      freez = 160;
                      break;
                    case 8:		//Kamikaze
                      showit = false;
                      if (fra - lastbo >= 30) {
                        lasth = 0;
                        lastbo = fra;
                        bombfail(trg.xp, trg.yp);
                      }
                      break;
                    case 5:		//Mr. Boom
                      showit = false;
                      bomb(true);
                      break;
                    case 6:		//Tammy's Head
                      e = 0;
                      while (e < 10) {
                        trg2 = create(trg.xp, trg.yp, 0, Math.sin((e / 5) * Math.PI) * 10, Math.cos((e / 5) * Math.PI) * 10, 0, 2);
                        trg2.d._xscale = 135.5;
                        trg2.d._yscale = 135.5;
                        ++e;
                      }
                      break;
                    case 12:	//Teleport!
                      showit = false;
                      teleport();
                      break;
                    case 13:	//Yum Heart
                      ++player.hp;
                      _root.soundy('Vamp_Gulp.mp');
                      break;
                    case 17:	//Shoop da Whoop
                      showit = false;
                      laser = 1;
                      break;
                    case 25:	//Anarchist's Cookbook
                      _root.over.gotoAndStop(6);
                      _root.soundy('Book Page Turn 12.wav', 100);
                      anarch = 30;
                      break;
                    case 26:	//The Hourglass
                      _root.over.gotoAndStop(7);
                      slow = 230;
                  }
                  if (showit) {
                    player.d.gotoAndStop(11);
                    player.it = _root.colit;
                    player.d.d.d.it.d.gotoAndStop(player.it);
                    player.d.d.d.it.d.p.gotoAndStop(player.pillItem);
                  }
                  if (itemChargeRates[_root.spacebarItem] > 0 && doit) {
                    if (haveEffect[116]) {
                      _root.itemCharges = 0.334;
                    } else {
                      _root.itemCharges = 0;
                    }
                    nocharge = 10;
                  }
                  if (goper) {
                    goper = false;
                    _root.spacebarItem = 84;
                  }
                }
              }
            } else {
              nosp = false;
            }
          }
          f1 = _root.bodyMode;
          if (demon > 0 or haveEffect[122]) {
            sk = 7;
          } else {
            sk = _root.sk;
          }
          if (haveEffect[20]) {
            f1 = 3;
            trg.flyby = true;
          }
          if (haveEffect[82]) {
            f1 = 9;
            trg.flyby = true;
          }
          if (bible or haveEffect[179] or haveEffect[184]) {
            f1 = 12;
            trg.flyby = true;
          }
          if (haveEffect[185]) {
            f1 = 23;
            trg.flyby = true;
          }
          if (sk == 7) {
            if (trg.flyby) {
              f1 = 9;
            } else {
              f1 = 8;
            }
          } else {
            if (sk == 5) {
              _root.headMode = 25;
              _root.bodyMode = 13;
            }
          }
          if (_root.spacebarItem == 8 && !haveEffect[20]) {
            f1 = 2;
          }
          if (haveEffect[159]) {
            f1 = 22;
            trg.flyby = true;
          }
          if (_root.spacebarItem == 90 or _root.spacebarItem == 141) {
            f1 = 16;
            trg.flyby = true;
            if (sk == 7) {
              f1 = 18;
            } else {
              if (sk == 5) {
                f1 = 17;
              }
            }
          }
          if (razor > 0 or haveEffect[189]) {
            if (trg.flyby) {
              f1 = 3;
            } else {
              f1 = 27;
            }
          }
          if (catMode) {
            f1 = 25;
            trg.flyby = true;
          }
          trg.d.bo.gotoAndStop(f1);
          if (enfget(trg.xbew, trg.ybew) < 2) {
            if (_root.spacebarItem != 90 or fra < 3) {
              trg.d.bo.d.gotoAndStop(1);
            }
          } else {
            f1 = Math.abs(trg.xbew) > Math.abs(trg.ybew);
            if (_root.spacebarItem == 9) {
              f1 = Math.abs(trg.xbew) * 0.5 > Math.abs(trg.ybew);
            }
            if (f1) {
              trg.d.bo.d.gotoAndStop(3);
              if (trg.xbew * trg.d.bo._xscale < -100) {
                trg.d.bo._xscale *= -1;
              }
            } else {
              if (_root.spacebarItem == 90 or _root.spacebarItem == 141) {
                if (trg.ybew > 0) {
                  trg.d.bo.d.gotoAndStop(1);
                } else {
                  trg.d.bo.d.gotoAndStop(2);
                }
              } else {
                trg.d.bo.d.gotoAndStop(2);
              }
              if (_root.spacebarItem == 90 or _root.spacebarItem == 141) {
                if (trg.xbew * trg.d.bo._xscale < -100) {
                  trg.d.bo._xscale *= -1;
                }
              }
            }
          }
          dirkey(true);
          horss(true);
          if (xenf == 0) {
            lastx = fra;
          }
          if (yenf == 0) {
            lasty = fra;
          }
          if (md) {
            xenf = _xmouse - trg.xp;
            yenf = _ymouse - trg.yp + 10;
            if (Math.abs(xenf) < Math.abs(yenf)) {
              xenf = 0;
            } else {
              yenf = 0;
            }
          }
          if (haveEffect[114]) {
            xxenf = xenf;
            yyenf = yenf;
          }
          if (nomove && !_root.bombnext && !chaf) {
            yenf = 0;
            xenf = 0;
          }
          if (missileTimer > 0) {
            drop.xbew *= 0.5;
            drop.ybew *= 0.5;
            if (!md) {
              drop.xbew += xenf * 8;
              drop.ybew += yenf * 8;
            } else {
              enfcheck(drop.xp, drop.yp, _xmouse, _ymouse, 10000);
              enf = (Math.min(enf / 3, 4) / enf) * 2;
              drop.xbew -= xenf * enf;
              drop.ybew -= yenf * enf;
            }
            yenf = 0;
            xenf = 0;
          } else {
            if (xenf != 0 && yenf != 0) {
              if (lasty > lastx) {
                xenf = 0;
              } else {
                yenf = 0;
              }
            }
          }
          v1 = plo;
          if (laser <= 1) {
            if (xenf != 0 or yenf != 0) {
              if (plox <= 8 && (!haveEffect[118] or trg.fire <= 0 or chaf == undefined or _root.bombnext)) {
                if (Math.abs(xenf) > Math.abs(yenf)) {
                  yenf = 0;
                  if (xenf > 0) {
                    xenf = 1;
                    plo = 2;
                  } else {
                    plo = 4;
                    xenf = -1;
                  }
                } else {
                  xenf = 0;
                  if (yenf < 0) {
                    plo = 3;
                    yenf = -1;
                  } else {
                    yenf = 1;
                    plo = 1;
                  }
                }
              }
              if (laser == 1) {
                trg.xpp = xenf;
                trg.ypp = yenf;
                yenf = 0;
                xenf = 0;
              }
              ++laser;
            }
          }
          if (haveEffect[68] && plox > 8) {
            plo = v1;
          }
          if (laser > 1) {
            trg.d.gotoAndStop(1);
            ++laser;
            trg.xbew *= 0.9;
            trg.ybew *= 0.9;
            if (laser > 21 && laser < 32 && fra % 3 != 0) {
              lasershow(trg);
            }
            if (laser > 40) {
              laser = undefined;
            }
            yenf = 0;
            xenf = 0;
          }
          if (haveEffect[114] && !_root.bombnext) {
            if (knil == undefined) {
              knil = 23;
              knill = 0;
              knife.xppp = trg.xp;
              knife.yppp = trg.yp;
              knife.xbew = trg.xbew;
              knife.ybew = trg.ybew;
            }
            if (_root.knif == undefined) {
              _root.knif = 0;
            }
            if (haveEffect[114]) {
              f1 = xxenf;
              f2 = yyenf;
              xxenf = xenf;
              yyenf = yenf;
              xenf = f1;
              yenf = f2;
            } else {
              xxenf = xenf;
              yyenf = yenf;
            }
            if (xenf != 0 or yenf != 0) {
              f1 = rotget(xenf, yenf) + 180;
              _root.knir = f1;
            } else {
              f1 = _root.knir;
            }
            knife.dmg = baseDamage() * (2 + Math.min(Math.max(knill, 0), 4));
            knil += knill;
            knill -= 1.4;
            f1 -= knife.d.z._rotation;
            f1 = absmax(rotrund(f1), Math.max(0, 40 - knil));
            knife.d.z._rotation += f1 * 0.7;
            _root.knif *= 0.98;
            if (knil < 23) {
              knil = 23;
              if ((xenf != 0 or yenf != 0) && Math.abs(f1) < 5) {
                firr(trg);
                _root.knif += Math.max(0.2, Math.min(0.35, (0.2 / trg.fire) * 10));
              }
              if (_root.knif > 0.35 && xenf == 0 && yenf == 0 && !kkk) {
                knill = Math.min(20, Math.max(10, _root.tearRange * 0.51) * (0.3 + _root.knif * 0.2));
                _root.knif = 0;
              }
              knife.xppp = trg.xp;
              knife.yppp = trg.yp;
              knife.xbew = trg.xbew;
              knife.ybew = trg.ybew;
            } else {
              if (knill < 0) {
                knife.xppp *= 0.5;
                knife.yppp *= 0.5;
                knife.xppp += trg.xp * 0.5;
                knife.yppp += trg.yp * 0.5;
              } else {
                knife.xppp *= 0.8;
                knife.yppp *= 0.8;
                knife.xppp += trg.xp * 0.2;
                knife.yppp += trg.yp * 0.2;
              }
            }
            f1 = (knife.d.z._rotation / 180) * Math.PI;
            if (knife.d.z._rotation < -90 or knife.d.z._rotation > 90) {
              knife.d.z._yscale = -100;
            } else {
              knife.d.z._yscale = 100;
            }
            if (fra > 3) {
              knife.xp = knife.xppp + Math.cos(f1) * knil;
              knife.yp = knife.yppp + Math.sin(f1) * knil * 0.8 - Math.cos(f1) * 3;
              knife.xppp += knife.xbew;
              knife.yppp += knife.ybew;
              knife.xbew *= 0.8;
              knife.ybew *= 0.8;
            }
            if (fra % 3 == 0) {
              knife.hh = [];
            }
            yenf = 0;
            xenf = 0;
          }
          if (haveEffect[118] && trg.d.d.d.d._currentframe > 4) {
            trg.d.d.d.d.z.nextFrame();
            if (trg.d.d.d.d.z._currentframe == 4 or trg.d.d.d.d.z._currentframe == 11) {
              brim = true;
              lasershow(trg);
              yenf = 0;
              xenf = 0;
              brim = false;
            }
          }
          f1 = _root.faceMode;
          f2 = _root.headMode;
          nohat = false;
          if (belial) {
            f1 = 8;
            f2 = 8;
          }
          if (haveEffect[3] && !_root.pickedUp[3]) {
            f1 = 4;
            f2 = 4;
          }
          if (sk != 5 && haveEffect[69]) {
            f2 = 17;
          }
          if (haveEffect[122]) {
            f2 = 30;
          } else {
            if (sk == 7) {
              if (haveEffect[159]) {
                f2 = 39;
              } else {
                if (haveEffect[80]) {
                  f2 = 20;
                } else {
                  f2 = 22;
                }
              }
            }
          }
          if (haveEffect[149]) {
            f2 = 36;
          }
          if (razor > 0) {
            f2 = 29;
          }
          if (haveEffect[189]) {
            f2 = 42;
          }
          if (catMode) {
            f2 = 43;
          }
          if (demon > 0) {
            f2 = 21;
          }
          if (haveEffect[68]) {
            if (sk == 5) {
              f2 = 28;
            } else {
              if (sk == 7) {
                f2 = 27;
              } else {
                f2 = 10;
              }
            }
            f1 = 12;
          }
          if (haveEffect[118]) {
            f2 = 31;
          }
          if (laser) {
            f2 = 14;
          }
          if (unic > 0) {
            if (pacman) {
              f2 = 23;
            } else {
              f2 = 19;
            }
            nohat = true;
          }
          facer = f2;
          if (trg.d._currentframe == 1 or _root.bombnext) {
            _root.tex = chaaf;
            _root.hud.weap.gotoAndStop(f1);
            if (Math.abs(xenf) < 0.5 && Math.abs(yenf) < 0.5 && !kkk && (haveEffect[69] or haveEffect[118]) && !_root.bombnext) {
              if (chaf > -1000 && Math.abs(chax) + Math.abs(chay) > 0) {
                if (chaaf > 4.7 or haveEffect[69]) {
                  chaz = true;
                  xenf = chax;
                  yenf = chay;
                } else {
                  chay = 0;
                  chax = 0;
                  chaf = undefined;
                  plo = 1;
                }
              }
            }
            if (pacman) {
              if (trg.d.d.d.d._xscale * trg.xbew < -300) {
                trg.d.d.d.d._xscale *= -1;
                if (trg.d.d.d.d._xscale < 0) {
                  trg.d.d.d.d._x = 40.7;
                } else {
                  trg.d.d.d.d._x = 0;
                }
              }
            } else {
              if (pacoo) {
                pacoo = false;
                trg.d.d.d.d._xscale = 100;
                trg.d.d.d.d._x = plxx;
              } else {
                plxx = trg.d.d.d.d._x;
              }
              if (Math.abs(xenf) > 0.5 or Math.abs(yenf) > 0.5 or haveEffect[114] && (xxenf != 0 or yyenf != 0)) {
                plff();
              } else {
                if (plox < 0 && laser <= 1 && !haveEffect[118]) {
                  plo = 1;
                }
                if (!haveEffect[118] or trg.fire < 4) {
                  trg.d.d.d.d.gotoAndStop(plo);
                }
              }
            }
            if (trg.d._currentframe == 1) {
              if (laser > 1) {
                trg.d.d.d.d.d.gotoAndStop(laser);
              }
              if (chaaf > 0) {
                trg.d.d.d.d.gotoAndStop(plo);
                if (trg.d.d.d.d._currentframe < 5) {
                  trg.d.d.d.d.d.gotoAndStop(chaaf);
                }
              } else {
                if (_root.headMode == 17 or haveEffect[118]) {
                  if (plox > 8) {
                    trg.d.d.d.d.gotoAndStop(plo + 4);
                  }
                }
              }
              if (haveEffect[68]) {
                haveEffect[103] = _root.pickedUp[103];
                if (haveTrinket(30)) {
                  if (random(10) == 0) {
                    haveEffect[103] = 0;
                  }
                }
                trg2 = player.d.d.d.d.l;
                if (haveEffect[115]) {
                  colorit(trg2, 1.5, 2, 2, 0, 0, 0);
                  trg2._alpha = 50;
                } else {
                  if (haveEffect[103]) {
                    colorit(trg2, 0.4, 0.97, 0.5, 0, 150, 0);
                  } else {
                    if (haveEffect[104]) {
                      colorit(trg2, 1, 0.4, 0.13, 30, 0, 0);
                    } else {
                      if (haveEffect[89]) {
                        colorit(trg2, 3, 3, 3, 150, 150, 150);
                      } else {
                        if (haveEffect[90]) {
                          colorit(trg2, 0.4, 0.4, 0.4, 100, 100, 100);
                        } else {
                          if (haveEffect[69]) {
                            colorit(trg2, 0.33, 0.18, 0.18, 66, 40, 40);
                          } else {
                            if (haveEffect[6]) {
                              colorit(trg2, 0.2, 1, 0, 255, 255, 0);
                            } else {
                              if (haveEffect[3]) {
                                colorit(trg2, 0.4, 0.15, 0.38, 90, 0, 180);
                              }
                            }
                          }
                        }
                      }
                    }
                  }
                }
                if (Math.abs(trg.xpp) > Math.abs(trg.ypp)) {
                  f1 = (lass / trg.d.d._xscale / trg._xscale) * 10000 + (trg2._x - 6) * trg.xpp - 13;
                } else {
                  f1 = (lass / trg.d.d._xscale / trg._xscale) * 10000 + (trg2._y + 20) * trg.ypp;
                }
                trg2._yscale = f1;
                trg2._xscale = laserDamage * 30;
                trg2._x -= trg.xp - lasx;
                trg2._y -= trg.yp - lasy;
                lasx = trg.xp;
                lasy = trg.yp;
              }
            }
          }
          chaaf = 0;
          --plox;
          --plox1;
          --trg.fire;
          --trg.fire1;
          dirkey(false);
          if (horse > 0) {
            if (horse == 100) {
              horss();
            } else {
              --horse;
              xenf = horsx * 4.5;
              yenf = horsy * 4.5;
              trg.xbew *= 0.7;
              trg.ybew *= 0.7;
              if (horse % 6 < 3) {
                colorit(player, 1.2, 1.2, 1.2, 55, 55, 55);
              }
            }
            hhorse = 10;
          } else {
            if (horse == undefined) {
              --hhorse;
            } else {
              horse = undefined;
            }
          }
          f1 = 100 + (haveEffect[12] - haveEffect[71] + haveEffect[122]) * 25;
          if (demon > 0) {
            f1 += 25;
          }
          if (haveEffect[157]) {
            f1 += (rag - 1) * 14;
          }
          trg._yscale = f1;
          trg._xscale = trg._yscale;
          if (trg.d._currentframe == 1) {
            f1 = 100 + (haveEffect[121] - haveEffect[120]) * 20;
            trg.d.d._yscale = f1;
            trg.d.d._xscale = trg.d.d._yscale;
          }
          f10 = [0, -0.15, 0.3, 0, 0.1, 0.23, 0.1];
          f1 = 1;
          _root.playsp = 1 + Math.min(1, (haveEffect[119] + haveEffect[27] + haveEffect[28] + haveEffect[12] + haveEffect[71] + haveEffect[101] + haveEffect[122] + haveEffect[120] + haveEffect[143]) * 0.3 + Math.min(1, haveEffect[14]) * 0.6 - Math.min(1, haveEffect[13] + haveEffect[121]) * 0.1 + f10[_root.characterID] + haveEffect[70] * 0.4 + haveEffect[79] * 0.2 + haveEffect[82] * 0.3) - (haveEffect[90] + haveEffect[129] + haveEffect[189]) * 0.2;
          if (unic > 0) {
            _root.playsp += 0.28;
          }
          if (haveTrinket(37)) {
            _root.playsp += 0.15;
          }
          if (demon > 0) {
            _root.playsp -= 0.18;
          }
          if (_root.spacebarItem == 90 or _root.spacebarItem == 141) {
            _root.playsp = Math.max(1.5, _root.playsp);
          }
          f1 = _root.playsp;
          xenf *= 0.75 + f1 * 0.25;
          yenf *= 0.75 + f1 * 0.25;
          nomove = trg.d._currentframe >= 3 && trg.d._currentframe < 9 or fra < 20;
          if (nomove) {
            yenf = 0;
            xenf = 0;
          }
          if (xenf == 0) {
            lastxx = fra;
          }
          if (yenf == 0) {
            lastxy = fra;
          }
          if (trg.ghhh) {
            if (xenf != 0 && yenf != 0) {
              if (lastxy > lastxx) {
                xenf = 0;
              } else {
                yenf = 0;
              }
            }
          } else {
            if (xenf != 0 && yenf != 0) {
              xenf /= Math.SQRT2;
              yenf /= Math.SQRT2;
            }
          }
          trg.ghhh = false;
          v1 = 0;
          if (xenf != 0 && yenf == 0) {
            v1 = Math.abs(trg.ybew);
            trg.ybew *= 0.5;
          } else {
            if (yenf != 0 && xenf == 0) {
              v1 = Math.abs(trg.xbew);
              trg.xbew *= 0.5;
            }
          }
          v1 *= 0.3;
          v2 = xenf * trg.xbew + trg.ybew * yenf;
          v1 = v1 * 0.1 + Math.max(0, v2 * 0.2);
          v1 = 3 + v1 / _root.playsp;
          v1 *= 0.8;
          trg.xbew -= xenf * v1;
          trg.ybew -= yenf * v1;
          trg.xbew *= 0.7 + _root.playsp * 0.075;
          trg.ybew *= 0.7 + _root.playsp * 0.075;
        }
        laps();
      }

      function posw(f1, f2, f3) {
        var v2 = -100;
        var v3 = -100;
        while (mhit(v2, v3) or levz[ingrid(v2, v3)] >= 0.6) {
          if (f3 > 500) {
            f3 = 0;
          }
          f3 += 5;
          v2 = f1 + crand(f3);
          v3 = f2 + crand();
          outgrid(ingrid(v2, v3));
          v2 = xenf;
          v3 = yenf;
          if (random(100) != 0) {
            for (z in ball) {
              var v1 = ball[z];
              if (v1.s == 5) {
                if (Math.abs(v1.xp - v2) < 20) {
                  if (Math.abs(v1.yp - v3) < 20) {
                    v2 = -100;
                  }
                }
              }
            }
          }
        }
      }

      function spaw(f1, f2, f3, f0) {
        posw(f1, f2, f3);
        levz[ingrid(xenf, yenf)] = 0.9;
        return create(xenf, yenf, 0, 0, 0, 0, f0);
      }

      function scerf() {
        if (bgg2 == undefined) {
          trg = createEmptyMovieClip('bggg2', 35670000);
          bgg2 = new flash.display.BitmapData(gridxs, gridys - f1, true, 0);
          trg.attachBitmap(bgg2, 1);
          trg._xscale = 100 / hdx;
          trg._yscale = trg._xscale;
          maxx = new flash.geom.Matrix();
          maxx.scale(hdx, hdx);
          bgg2.draw(this, maxx);
        }
      }

      function dirkey(f1) {
        enf = 0;
        yenf = 0;
        xenf = 0;
        kkk = false;
        if (_root.so.data.left) {
          f1 = !f1;
        }
        if (!f1) {
          if (_root.so.data.frog) {
            if (Key.isDown(81)) {
              kkk = true;
              ++xenf;
            }
            if (Key.isDown(90)) {
              kkk = true;
              ++yenf;
            }
          } else {
            if (Key.isDown(65)) {
              kkk = true;
              ++xenf;
            }
            if (Key.isDown(87)) {
              kkk = true;
              ++yenf;
            }
          }
          if (Key.isDown(68)) {
            kkk = true;
            --xenf;
          }
          if (Key.isDown(83)) {
            kkk = true;
            --yenf;
          }
        } else {
          if (Key.isDown(39)) {
            kkk = true;
            ++xenf;
          }
          if (Key.isDown(37)) {
            kkk = true;
            --xenf;
          }
          if (Key.isDown(38)) {
            kkk = true;
            --yenf;
          }
          if (Key.isDown(40)) {
            kkk = true;
            ++yenf;
          }
        }
        if (_root.so.data.left) {
          xenf *= -1;
          yenf *= -1;
        }
      }

      function xox(f3) {
        return random(10) == 0 or f3 && random(2) == 0;
      }

      function trinketForcedSpawn(f3) {
        if (haveTrinket(34) or haveTrinket(36) or haveTrinket(41) or haveTrinket(44) or haveTrinket(45)) {
          if (xox(f3) && haveTrinket(45)) {
            f2 = 5.3;
          } else {
            if (xox(f3) && haveTrinket(44)) {
              f2 = 5.07;
            } else {
              if (xox(f3) && haveTrinket(41)) {
                f2 = 5.04;
              } else {
                if (xox(f3) && haveTrinket(36)) {
                  if (random(2) == 0) {
                    f0 = 5.06;
                  } else {
                    f0 = 5.03;
                  }
                } else {
                  if (xox(f3) && haveTrinket(34)) {
                    f2 = 5.01;
                  }
                }
              }
            }
          }
        }
      }

      function replacePillColor(f2) {
        if (random(2) == 0) {
          _root.pillColors[random(6)] = f2;
        }
      }

      function pillColor(f1) {
        if (f1 < 7) {
          f1 = _root.pillColors[f1 - 1];
        }
        return f1;
      }

      function cspawn(f0, f12) {
        i = 0;
        while (i < f12) {
          f13 = 0;
          while (f13++ < 10) {
            xenf = crand(5);
            yenf = crand(5);
            if (_root.lev == _root.arenaRoom) {
              xenf *= 0.4;
              yenf *= 0.4;
            }
            if (linecheckx(chestox, chestoy, trg.xp + xenf * 7, trg.yp + yenf * 7)) {
              f13 = 1000;
            }
          }
          if (f0 == 5.05 or f0 == 5.06) {
            xenf = 0;
            yenf = 0;
            if (trg != 2) {
              chestoy += 10;
            }
          }
          var v2 = create(chestox, chestoy, 0, xenf, yenf, 0, f0);
          v2.alt = true;
          if (f0 == 5.1) {
            v2.fra -= 15;
            trg.done = true;
            if (trg == 2 && _root.SecretUnlocked[18] && !haveEffect[90]) {
              v2.alt = false;
              v2.it = 90;
            }
          }
          if (f0 == 5 && trg == 2) {
            v2.col = 3;
          }
          if (f0 == 5.05 or f0 == 5.06) {
            if (trg != 2) {
              v2._xscale = trg._xscale * 0.8;
              v2._yscale = v2._xscale;
            }
          }
          if (f10 < 0) {
            break;
          }
          ++i;
        }
      }

      function onEnterFrame() {
        _root.tex = '';
        for (e in shiz) {
          trg = shiz[e];
          if (trg.fra < fra) {
            trg.gotoAndStop(6);
            levz[trg.til] = 1.5;
            shiz.splice(e, 1);
          }
        }
        if (blueFlies == undefined) {
          blueFlies = _root.blueFlies;
        }
        if (fra == 14 && curss) {
          displayBannerMessage(curss);
        }
        if (haveEffect[114]) {
          haveEffect[118] = 0;
          haveEffect[69] = 0;
        }
        if (playfirst) {
          player.d.gotoAndStop(1);
          playfirst = false;
        }
        _root.chaf = chaf != undefined;
        if (player.dones) {
          if (gameover == 2) {
            ++_root.so.data.timesDied;
            if (_root.so.data.timesDied >= 100) {
              _root.SecretUnlocked[39] = true;
            }
          }
          if (gameover > 1) {
            if (!_root.pickedUp[11] && _root.pickedUp[81] <= 0 && !_root.pickedUp[161]) {
              if (!_root.dmusic) {
                _root.dmusic = true;
                _root.fade = true;
              }
            }
            if (_root.prsk) {
              _root.sk = _root.prsk;
              _root.characterID = _root.prsk2;
              _root.prsk = undefined;
              _root.prsk2 = undefined;
            }
          }
          if (gameover++ > 50) {
            if (_root.pickedUp[11] or _root.pickedUp[81] > 0 or _root.pickedUp[161]) {
              _root.armor = 0;
              if (ahsut <= 0) {
                _root.beenlev[_root.lev] = false;
              }
              _root.shroom = true;
              if (!_root.pickedUp[11]) {
                if (_root.characterID == 4) {
                  _root.armor = 1;
                  _root.pickedUp[23] += -player.mhp;
                } else {
                  _root.pickedUp[23] += 1 - player.mhp;
                }
                if (!_root.pickedUp[161]) {
                  _root.shroom = 2;
                  --_root.pickedUp[81];
                } else {
                  _root.shroom = 4;
                  _root.pickedUp[161] = 0;
                  if (_root.characterID != 4) {
                    --_root.pickedUp[23];
                    hat(31);
                    _root.prsk = _root.sk;
                    _root.prsk2 = _root.characterID;
                    _root.characterID = 4;
                    _root.sk = 5;
                  }
                  _root.armor = 3;
                }
              } else {
                if (_root.characterID == 4) {
                  _root.armor = 3;
                }
              }
              _root.pickedUp[11] = 0;
              _root.door = _root.door * 1 + 2;
              if (_root.door >= 4) {
                _root.door -= 4;
              }
              _root.playerx = 320;
              _root.playery = 400;
              invp();
              _root.old.fillRect(_root.old.rectangle, 0);
              _root.old.draw(this);
              _root.olda._x = 0;
              _root.olda._y = 0;
              _root.olda._visible = true;
              _root.lev = _root.lastl;
              if (_root.lev <= 0) {
                _root.lev = 35;
                _root.lastl = 35;
              }
              _root.hp = 1000;
              _root.getup = true;
              moveon();
              _root.gotoAndStop('reset');
            } else {
              _root.map.fillRect(_root.map.rectangle, 0);
              _root.hud.paus.gotoAndStop(3);
              if (lastk <= 0) {
                lastk = 1;
              }
              _root.hud.paus.kill.gotoAndStop(Math.round(lastk));
              _root.hud.paus.nam.gotoAndStop(Math.max(1, _root.characterID));
              _root.hud.paus.loco.gotoAndStop(Math.max(1, _root.floorNum));
              onEnterFrame = undefined;
            }
          }
        }
        if (_root.catlives + haveEffect[145] + haveEffect[134] + haveEffect[133] > 2) {
          _root.SecretUnlocked[85] = true;
          catMode = true;
        }
        player.d.bub2._visible = haveEffect[108] or haveEffect[162] or haveEffect[173] or haveEffect[142] or haveEffect[184];
        if (haveEffect[184]) {
          player.d.bub2.gotoAndStop(5);
        } else {
          if (haveEffect[142]) {
            player.d.bub2.gotoAndStop(2);
          } else {
            if (haveEffect[173]) {
              player.d.bub2.gotoAndStop(3);
            } else {
              if (haveEffect[108]) {
                player.d.bub2.gotoAndStop(1);
              } else {
                player.d.bub2.gotoAndStop(4);
              }
            }
          }
        }
        player.d.bub._visible = playsave > 0;
        if (player.d.bub._visible) {
          if (playsave < 50) {
            if (playsave % 5 == 0) {
              co = !co;
              if (co) {
                player.d.bub._alpha = 100;
              } else {
                player.d.bub._alpha = 0;
              }
            }
          }
        }
        if (fra == telf) {
          _root.door = undefined;
          _root.soundy('hell_portal1.wav');
          if (shutdoor != 0) {
            _root.beenlev[_root.lev] = false;
          }
          moveon();
          if (teleportTarget) {
            _root.lev = teleportTarget;
          } else {
            while (_root.lev == _root.lastl or !_root.levz[_root.lev] or _root.lev > 150) {
              _root.lev = random(_root.levz.length) + 1;
            }
          }
          if (_root.lev == _root.bossRoom && _root.labyrinthCurse && _root.bossID != _root.bossID2) {
            _root.lev = _root.bossRoom2;
          }
          _root.tell = true;
          _root.door = undefined;
          _root.lastl = undefined;
          _root.gotoAndStop('reset');
        }
        if (fra % 3 == 0) {
          for (e in bomf) {
            bombfail(bomf[e][0], bomf[e][1], bomf[e][2], bomf[e][3]);
          }
          bomf = [];
        }
        if (haveEffect[144] && !bumz) {
          bumz = true;
          trg2 = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          trg2.bum = true;
          trg2.flyby = true;
        }
        if (haveEffect[114] && knife == undefined && player.d._currentframe < 3) {
          trg = create(player.xp, player.yp - 10, 0, 0, 0, 0, 2);
          knife = trg;
          attach(trg, 501);
          trg.dy = undefined;
          trg.knife = true;
        }
        if (haveEffect[81] && !cats && player.d._currentframe < 3) {
          cats = true;
          trg = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          trg.cat = true;
        }
        if (haveEffect[11] && !catss && player.d._currentframe < 3) {
          catss = true;
          trg = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          trg.cat = 2;
        }
        if (haveEffect[94] && !monb && player.d._currentframe < 3) {
          monb = true;
          trg = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          trg.mon = 1;
        }
        if (haveEffect[96] && !monb2 && player.d._currentframe < 3) {
          monb2 = true;
          trg = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          trg.mon = 2;
        }
        if (haveEffect[98] && !monb3 && player.d._currentframe < 3) {
          monb3 = true;
          trg = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          trg.mon = 3;
        }
        if (haveEffect[131] && !monb4 && player.d._currentframe < 3) {
          monb4 = true;
          trg = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          trg.mon = 4;
        }
        if (haveEffect[73] && !meats && player.d._currentframe < 3) {
          meats = true;
          trg = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          trg.meat = true;
        }
        if (haveEffect[73] > 4 && !meats2 && player.d._currentframe < 3) {
          meats2 = true;
          trg = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          trg.meat = true;
          trg.me2 = true;
        }
        if (Math.min(2, haveEffect[112]) > flyby4 && player.d._currentframe < 3) {
          ++flyby4;
          trg2 = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          trg2.ang = true;
        }
        if (Math.min(3, haveEffect[8] + haveEffect[67] + haveEffect[95] + haveEffect[99] + haveEffect[100] + haveEffect[113] + haveEffect[163] + haveEffect[167] + haveEffect[174] + haveEffect[188]) > minions && player.d._currentframe < 3) {
          ++minions;
          create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
        }
        if (haveEffect[155] && player.d._currentframe < 3 && !eyepie) {
          eyepie = true;
          trg2 = create(player.xp, player.yp - 10, 0, crand(10), crand(10), 0, 3);
          trg2.peeper = true;
        }
        if (haveEffect[187] && player.d._currentframe < 3 && !hairball) {
          hairball = true;
          trg2 = create(player.xp, player.yp - 10, 0, crand(10), crand(10), 0, 3);
          trg2.hairball = true;
        }
        if (haveEffect[178] && player.d._currentframe < 3 && !holp) {
          holp = true;
          trg2 = create(player.xp, player.yp - 10, 0, crand(10), crand(10), 0, 3);
          trg2.hol = true;
          holyWater = trg2;
        }
        if (haveEffect[172] && player.d._currentframe < 3 && !knip) {
          knip = true;
          trg2 = create(player.xp, player.yp - 10, 0, crand(10), crand(10), 0, 3);
          trg2.ni = true;
        }
        if (haveEffect[117] == 0.55) {
          haveEffect[117] = 0;
          trg2 = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          trg2.bird = true;
        }
        if (dbird == 2) {
          dbird = 1;
          trg2 = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          trg2.bird = 2;
        }
        if (haveTrinket(57) && ggho == undefined && player.d._currentframe < 3) {
          trg2 = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          ggho = trg2;
          trg2.ggho = true;
        }
        if (!haveTrinket(57) && ggho) {
          ggho.done = true;
          ggho = undefined;
        }
        if (haveTrinket(54) && ggho2 == undefined && player.d._currentframe < 3) {
          trg2 = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          ggho2 = trg2;
          trg2.ggho = 2;
        }
        if (!haveTrinket(54) && ggho2) {
          ggho2.done = true;
          ggho2 = undefined;
        }
        if (haveEffect[170] && !dad) {
          dad = true;
          trg2 = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          trg2.dad = true;
          trg2.d.gotoAndStop(151);
          trg2.d.d.gotoAndStop(1);
        }
        if (bodd && player.d._currentframe < 3) {
          bodd = false;
          trg2 = spaw(trg.xp, trg.yp, 0, 3);
          trg2.meat = 5;
          colorit(trg2, _root.playerTint[0], _root.playerTint[1], _root.playerTint[2], 0, 0, 0);
        }
        if (Math.min(3, haveEffect[10] * 2) > flyby && player.d._currentframe < 3) {
          ++flyby;
          trg = create(player.xp, player.yp, 0, 0, 0, 0, 3);
          trg.fly = true;
        }
        if (Math.min(1, haveEffect[57]) > flyby2 && player.d._currentframe < 3) {
          ++flyby2;
          trg = create(player.xp, player.yp, 0, 0, 0, 0, 3);
          trg.fly = true;
          trg.alt = true;
        }
        if (Math.min(1, haveEffect[128]) > flyby3 && player.d._currentframe < 3) {
          ++flyby3;
          trg = create(player.xp, player.yp, 0, 0, 0, 0, 3);
          trg.fly = true;
          trg.alt = 2;
        }
        if (haveEffect[88] && !magsss && player.d._currentframe < 3) {
          magsss = true;
          trg = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
          trg.maga = true;
        }
        if (blueFlies > 0) {
          if (player.d._currentframe < 3) {
            --blueFlies;
            trg2 = create(player.xp, player.yp - 10, 0, 0, 0, 0, 3);
            trg2.blueFlies = true;
            trg2.fly = true;
            if (blueFlyTarget != undefined) {
              trg2.trg2 = blueFlyTarget;
              blueFlyTarget = undefined;
              trg2.xbew += crand(10);
              trg2.ybew += crand(10);
            }
          }
        } else {
          blueFlies = 0;
        }
        gibb += ball.length * 0.1 - 0.4;
        gibb *= 0.9;
        for (e in door) {
          trg = door[e];
          if (trg._visible && levz[trg.blo] == 0 && (justnow < 10 or trg.hide or trg.hide2)) {
            trg.blown = true;
            if (trg.hide or trg.hide2) {
              if (trg.hide2) {
                revealSecretRoom2();
              } else {
                revealSecretRoom();
              }
              trg.gotoAndStop(17);
            } else {
              if (!keyo) {
                if (mom.length > 4 or _root.lev == _root.minibossRoom) {
                  levz[trg.blo] = 1;
                  trg.blown = false;
                } else {
                  trg.gotoAndStop(5);
                }
              }
            }
          }
          if (trg.blown && levz[trg.blo] < 1) {
            levz[trg.blo] = 0.9;
          }
        }
        if (haveEffect[75] && random(150) == 0) {
          identifyPill();
        }
        f1 = _root.spacebarItem;
        if (f1 < 1) {
          f1 = 'empty';
          _root.itemCharges = 1;
          _root.hud.it.gotoAndStop(7);
          _root.hud.it.d.gotoAndStop(20);
        }
        f10 = [3, 4, 2, 1, 3, 2, 1];
        player.mhp = Math.min(f10[_root.characterID] + haveEffect[22] + haveEffect[23] + haveEffect[121] + haveEffect[24] + haveEffect[25] + haveEffect[26] + haveEffect[12] + haveEffect[101] + haveEffect[15] + haveEffect[92] + haveEffect[119] + haveEffect[16] * 2 + haveEffect[129] * 2 + haveEffect[176] + haveEffect[184] + haveEffect[193] + haveEffect[189] + haveEffect[138], 12);
        if (_root.characterID == 4) {
          if (player.mhp > 0) {
            --_root.pickedUp[22];
            haveEffect[22] = _root.pickedUp[22];
            ++_root.armor;
          }
          player.mhp = 0;
        }
        if (player.mhp >= 7) {
          _root.SecretUnlocked[1] = true;
        }
        if (player.hp > mhpp) {
          if (fra > 10) {
            if (player.hp - mhpp > 0.55) {
              red = 7;
            } else {
              red = 4;
            }
          }
        }
        mhpp = player.hp;
        if (_root.armor > ahpp) {
          if (fra > 10) {
            blue = 7;
          }
        }
        if (player.hp > 0) {
          player.hp = Math.max(0.5, Math.min(player.mhp, player.hp));
        }
        if (_root.itemCharges >= 0.9) {
          _root.itemCharges = 1;
          if (_root.hud.it._currentframe <= 14) {
            _root.hud.it.nextFrame();
          } else {
            if (itb-- < 0) {
              _root.hud.it.gotoAndStop(15);
            }
          }
        } else {
          if (itb-- > 0) {
            _root.hud.it.gotoAndStop(16);
          } else {
            hudder = _root.hud.it._currentframe;
            _root.hud.it.gotoAndStop(Math.round(_root.itemCharges * 6 - 0.5) + 1);
          }
        }
        _root.hud.extra2._visible = _root.trinketSlot1 != undefined;
        if (_root.hud.extra2._visible) {
          _root.hud.extra2.d.gotoAndStop(11);
          _root.hud.extra2.d.p.gotoAndStop(_root.trinketSlot1);
          _root.hud.tex2 = _root.trinket1;
          f11 = _root.hud.tex2.split('');
          _root.hud.black._xscale = f11.length * 7 + 20;
          _root.hud.extra2.d._alpha = 100;
          if (_root.hud.plix._currentframe > 2) {
            _root.hud.plix.gotoAndStop(1);
          }
        } else {
          if (_root.hud.plix._currentframe < 3) {
            _root.hud.plix.gotoAndStop(4);
          }
          _root.hud.extra2.d._alpha = 0;
          _root.hud.tex2 = '';
          _root.hud.black._xscale = 0.1;
        }
        _root.hud.extra3._visible = _root.trinketSlot2 != undefined;
        if (_root.hud.extra3._visible) {
          _root.hud.extra3.d.gotoAndStop(11);
          _root.hud.extra3.d.p.gotoAndStop(_root.trinketSlot2);
          _root.hud.tex3 = _root.atrixer;
          f11 = _root.hud.tex3.split('');
          _root.hud.black2._xscale = f11.length * 7 + 20;
          _root.hud.extra3.d._alpha = 100;
          if (_root.hud.plix2._currentframe > 2) {
            _root.hud.plix2.gotoAndStop(1);
          }
        } else {
          if (_root.hud.plix2._currentframe < 3) {
            _root.hud.plix2.gotoAndStop(4);
          }
          _root.hud.extra3.d._alpha = 0;
          _root.hud.tex3 = '';
          _root.hud.black2._xscale = 0.1;
        }
        _root.hud.extra._visible = _root.pillItem != undefined;
        if (_root.hud.extra._visible) {
          f1 = _root.spacebarItem;
          _root.hud.extra.d.gotoAndStop(11);
          _root.hud.extra.d.p.gotoAndStop(pillColor(_root.pillItem));
          if (_root.pillItem > 6) {
            _root.hud.pilll.tex = tarotText(_root.pillItem, true);
          } else {
            f10 = !haveEffect[46] && !haveEffect[75];
            f11 = Math.round(_root.pillEffects[_root.pillItem]);
            if (f11 != _root.pillEffects[_root.pillItem]) {
              f2 = true;
            } else {
              f2 = false;
            }
            if (!f10) {
              f2 = true;
            }
            if (!_root.pillEffects[_root.pillItem]) {
              f11 = '???';
            } else {
              switch (Math.round(f11)) {
                case 14:
                  if (f2) {
                    f11 = 'Luck Up';
                  } else {
                    f11 = 'Luck Down';
                  }
                  break;
                case 13:
                  f11 = 'Friends till the end!';
                  break;
                case 6:
                  if (player.hp + _root.armor > 1) {
                    f11 = 'Bad Trip!';
                  } else {
                  case 1:
                    f11 = 'Full Health';
                    break;
                  case 2:
                    f11 = 'I found Pills';
                    break;
                  case 3:
                    f11 = 'Explosive Diarrhea!';
                    break;
                  case 4:
                    f11 = 'Balls of Steel';
                    break;
                  case 5:
                    f11 = 'Pretty Fly';
                    break;
                  case 7:
                    if (_root.characterID != 4) {
                      f13 = player.mhp;
                    } else {
                      f13 = _root.armor;
                    }
                    if (f13 <= 1 or f2) {
                      f11 = 'Health Up';
                    } else {
                      f11 = 'Health Down';
                    }
                    break;
                  case 8:
                    f11 = 'Bombs are Key';
                    break;
                  case 9:
                    if (f2) {
                      f11 = 'Tears Up';
                    } else {
                      f11 = 'Tears Down';
                    }
                    break;
                  case 10:
                    if (f2 or haveEffect[6] && _root.floorNum < 8) {
                      f11 = 'Range Up';
                    } else {
                      f11 = 'Range Down';
                    }
                    break;
                  case 11:
                    if (f2) {
                      f11 = 'Speed Up';
                    } else {
                      f11 = 'Speed Down';
                    }
                    break;
                  case 12:
                    f11 = 'Bad Gas';
                    break;
                  case 126:
                    f11 = 'TelePills';
                  }
              }
            }
            _root.hud.pilll.tex = f11;
          }
          f11 = _root.hud.pilll.tex.split('');
          _root.hud.pilll.black._xscale = f11.length * 7 + 20;
          _root.hud.extra.d._alpha = 100;
          if (_root.hud.pilll._currentframe > 2) {
            _root.hud.pilll.gotoAndStop(1);
          }
        } else {
          if (_root.hud.pilll._currentframe < 3) {
            _root.hud.pilll.gotoAndStop(4);
          }
          _root.hud.it.d._alpha = 100;
        }
        if (_root.goldenKey) {
          _root.hud.goldenKey.gotoAndStop(2);
        } else {
          _root.hud.goldenKey.gotoAndStop(1);
        }
        if (f1 > 0 or f1 == 'empty') {
          _root.hud.it.d.gotoAndStop(f1);
        }
        _root.keys = Math.min(99, _root.keys);
        _root.coins = Math.min(99, _root.coins);
        _root.bombs = Math.min(99, _root.bombs);
        if (_root.coins >= 55) {
          _root.SecretUnlocked[2] = true;
        }
        _root.hud.coins = _root.coins;
        _root.hud.bombs = _root.bombs;
        _root.hud.keys = _root.keys;
        lives = 1;
        if (haveEffect[11]) {
          ++lives;
        }
        if (haveEffect[81]) {
          lives += haveEffect[81];
        }
        if (lives > 1) {
          _root.hud.lives = 'x' + lives;
        } else {
          _root.hud.lives = '';
        }
        _root.hud.floorName = levelNames[_root.floorNum];
        if (_root.altchap) {
          _root.hud.floorName = alternateLevelNames[_root.floorNum];
        }
        if (_root.labyrinthCurse) {
          _root.hud.floorName = (_root.hud.floorName.split(' 2')).join('');
          _root.hud.floorName += ' XL';
        }
        if (_root.hud.keys < 10) {
          _root.hud.keys = '0' + _root.hud.keys;
        }
        if (_root.hud.bombs < 10) {
          _root.hud.bombs = '0' + _root.hud.bombs;
        }
        if (_root.hud.coins < 10) {
          _root.hud.coins = '0' + _root.hud.coins;
        }
        _root.mhp = player.mhp;
        _root.hp = player.hp;
        if (fra % 7 == 0) {
          if (blackout == 2) {
            bloc = new flash.geom.ColorTransform();
            bloc.redMultiplier = 0;
            bloc.greenMultiplier = 0;
            bloc.blueMultiplier = 0;
          } else {
            if (blackout) {
              bloc = new flash.geom.ColorTransform();
              bloc.redMultiplier = 0.15 + Math.random() * 0.15;
              bloc.greenMultiplier = 0.15 + Math.random() * 0.15;
              bloc.blueMultiplier = 0.15 + Math.random() * 0.15;
            } else {
              bloc = new flash.geom.ColorTransform();
              bloc.redMultiplier = 0.85 + Math.random() * 0.15;
              bloc.greenMultiplier = 0.85 + Math.random() * 0.15;
              bloc.blueMultiplier = 0.85 + Math.random() * 0.15;
            }
          }
        }
        trg = _root.hud.lif;
        f1 = _root.armor;
        f2 = red-- > 0;
        f3 = blue-- > 0;
        ahpp = _root.armor;
        if (_root.eternalHeart) {
          ++f1;
          ++ahpp;
          f4 = true;
        } else {
          f4 = false;
        }
        e = 0;
        while (e < 12) {
          trg2 = trg['h' + e];
          if (e >= player.mhp) {
            if (f1-- > 0) {
              trg2._visible = true;
              if (f4) {
                f4 = false;
                trg2.gotoAndStop(8);
              } else {
                if (f1 > -0.5) {
                  trg2.gotoAndStop(5);
                } else {
                  trg2.gotoAndStop(6);
                }
              }
              if (f3) {
                colorit(trg2, 1.6, 1.6, 2, 20, 20, 60);
              } else {
                colorit(trg2, 1, 1, 1, 0, 0, 0);
              }
            } else {
              trg2._visible = false;
            }
          } else {
            trg2._visible = true;
            trg2.gotoAndStop(Math.max(1, Math.min(3, (e - player.hp) * 2 + 3)));
            if (f2 && trg2._currentframe != 3) {
              colorit(trg2, 2, 1.6, 1.6, 100, 0, 0);
            } else {
              colorit(trg2, 1, 1, 1, 0, 0, 0);
            }
          }
          ++e;
        }
        trg2 = trg.h0;
        if (!f2) {
          if (player.hp < 1 && player.mhp >= 1) {
            if (fra % 10 == 0) {
              if (fra % 20 == 0) {
                colorit(trg2, 2, 1.6, 1.6, 100, 0, 0);
              } else {
                colorit(trg2, 1, 1, 1, 0, 0, 0);
              }
            }
          } else {
            colorit(trg2, 1, 1, 1, 0, 0, 0);
          }
        }
        if (enfget(_x, _y) < 2) {
          _root.olda._visible = false;
          _y = 0;
          _x = 0;
        } else {
          if (_root.door != undefined) {
            v1 = 0.5 + Math.min(enfget(_x, _y) * 0.004, 0.22);
            _x = _x * v1;
            _y = _y * v1;
            _root.olda._x = _x - olfx;
            _root.olda._y = _y - olfy;
            _root.olda._visible = true;
          }
        }
        f1 = 40;
        if (olfy > 0) {
          _root.olda._y += f1;
        } else {
          if (olfy < 0) {
            _root.olda._y -= f1;
          }
        }
        if (Key.isDown(82)) {
          if (resee++ > 30) {
            _root.fade = true;
            newstart(true);
          }
        } else {
          resee = 0;
        }
        if (Key.isDown(78)) {
        }
        if (Key.isDown(79)) {
          unpause = false;
          _root.hud.paus.gotoAndStop(5);
        }
        if (Key.isDown(73)) {
        }
        nogridyet = true;
        if (!sadfa) {
          sadfa = true;
          if (_root.lev == 80) {
            boss.swapDepths(1002088);
            for (e in levz) {
              outgrid(e);
              if (xenf > 440) {
                levz[e] = 1;
              }
            }
          }
        } else {
          if (!wetwwer) {
            wetwwer = true;
            golev();
            _root.black.prevFrame();
          } else {
            _root.fullhp = player.hp + _root.armor >= player.mhp;
            if (arenaActive) {
              f1 = (_root.arenaActive or (_root.fullhp && !_root.bossArena or _root.bossArena && player.hp < 1.5 or _root.lev == _root.arenaRoom) && arenaActive == 1) && shutdoor == 0 or keyd;
              for (e in door) {
                trg = door[e];
                if (trg.arenaRoom) {
                  if (!f1) {
                    v1 = trg.blo;
                    levz[v1] = 2;
                    clevc[v1] = 2;
                    trg.gotoAndStop(26);
                  } else {
                    v1 = trg.blo;
                    levz[v1] = 0;
                    clevc[v1] = 0;
                    if (trg._currentframe != 27 && trg._currentframe != 25) {
                      trg.gotoAndStop(25);
                    }
                  }
                }
              }
              if (arenaActive > 1 && !_root.arenaActive) {
                if (!_root.amusic) {
                  _root.amusic = true;
                  _root.fade = true;
                  _root.mmus.dones = true;
                }
                if (shutdoor == 0) {
                  if (arenaRoom++ > 50) {
                    mhelps = 0;
                    f1 = _root.switchero;
                    if (_root.floorNum % 2 == 1) {
                      f1 = !f1;
                    }
                    if (_root.bossArena) {
                      if (_root.floorNum < 5) {
                        f0 = [20, 1, 19, 3];
                      } else {
                        if (_root.floorNum < 7) {
                          f0 = [28, 4, 68, 1];
                        } else {
                          f0 = [69, 1, 43, 1];
                        }
                      }
                    } else {
                      if (_root.floorNum < 3) {
                        if (f1) {
                          f0 = [18, 5, 14, 5, 10, 4];
                        } else {
                          f0 = [29, 3, 12, 3, 15, 2];
                        }
                      } else {
                        if (_root.floorNum < 5) {
                          if (f1) {
                            f0 = [23, 5, 24, 4, 26, 4];
                          } else {
                            f0 = [31, 5, 22, 3, 27, 3];
                          }
                        } else {
                          if (_root.floorNum < 7) {
                            if (f1) {
                              f0 = [38, 4, 29, 5, 41, 4];
                            } else {
                              f0 = [39, 3, 34, 4, 24.4, 4];
                            }
                          } else {
                            if (f1) {
                              f0 = [19, 3, 28, 4, 20, 2];
                            } else {
                              f0 = [71, 1, 69, 1, 28, 1];
                            }
                          }
                        }
                      }
                    }
                    f1 = f0[(arenaActive - 2) * 2];
                    f2 = f0[(arenaActive - 2) * 2 + 1];
                    f3 = 0;
                    f6 = (Math.PI / f2) * 2;
                    e = 0;
                    while (e < f2) {
                      f4 = Math.sin(f3) * 200 + 320;
                      f5 = Math.cos(f3) * 180 + 250;
                      if (enfcheck(f4, f5, player.xp, player.yp, 40)) {
                        f3 += f6 / 2;
                        --e;
                      } else {
                        f3 += f6;
                        _root.soundy('summonsound.wav', 150);
                        if (f1 == 19 or f1 == 28) {
                          trg = spaw(f4 + 10, f5, 0, f1);
                          trg2 = spaw(f4, f5, 0, f1);
                          if (f1 == 28 or _root.bossArena) {
                            trg3 = spaw(f4 - 10, f5, 0, f1);
                          }
                          trg.xp = trg2.xp + 20;
                          trg3.xp = trg2.xp - 20;
                          trg.yp = trg2.yp;
                          trg3.yp = trg2.yp;
                          if (f1 == 28 && f2 > 2) {
                            f1 = 23;
                          }
                        } else {
                          spaw(f4, f5, 0, f1);
                        }
                      }
                      ++e;
                    }
                    ++arenaActive;
                    if (arenaActive > 4) {
                      justnow = 7;
                      _root.arenaActive = true;
                    }
                    arenaRoom = 30;
                  }
                }
              }
            }
            if ((keyd && !keyo or shutdoor == 0) && unpause) {
              if (shutdoor == 0) {
                ++justnow;
              }
              if (justnow == 10 or keyd && !keyo) {
                keyo = true;
                if (fra > 20) {
                  _root.soundy('Door_Heavy_Open.mp');
                }
                for (e in door) {
                  trg = door[e];
                  nohit = false;
                  if (trg.cus) {
                    trg.gotoAndStop(37);
                  } else {
                    if (trg.secretRoom or trg.secretRoom2) {
                      nohit = true;
                    } else {
                      if (trg.boner2) {
                        if (_root.treasureRoom2Opened) {
                          trg.gotoAndStop(33);
                        } else {
                          nohit = true;
                        }
                      } else {
                        if (trg.boner) {
                          if (_root.treasureRoomOpened) {
                            trg.gotoAndStop(33);
                          } else {
                            nohit = true;
                          }
                        } else {
                          if (trg.shop or trg.lib) {
                            if (_root.shopa && trg.shop or _root.libraryUnlocked && trg.lib) {
                              trg.gotoAndStop(1);
                            } else {
                              nohit = true;
                            }
                          } else {
                            if (trg.arcadeRoom) {
                              if (_root.payedArcadeFee) {
                                trg.gotoAndStop(21);
                              } else {
                                nohit = true;
                              }
                            } else {
                              if (trg.arenaRoom) {
                                if (fra < 15) {
                                  trg.gotoAndStop(27);
                                }
                              } else {
                                if (trg.sat) {
                                  if (satan) {
                                    if (_root.godRoomFloor) {
                                      trg.gotoAndStop(41);
                                    } else {
                                      trg.gotoAndStop(19);
                                    }
                                  } else {
                                    f1 = Math.min(0.3, haveEffect[51] * 0.2) + 0.01;
                                    if (_root.spacebarItem == 2) {
                                      f1 += 0.25;
                                    }
                                    if (_root.spacebarItem == 38) {
                                      f1 += 0.35;
                                    }
                                    if (_root.beggarKilled) {
                                      f1 += 0.35;
                                    }
                                    if (noBossDamage) {
                                      f1 += 0.35;
                                    }
                                    if (_root.devil) {
                                      f1 += 0.99;
                                    }
                                    if (_root.lastdev + 3 > _root.floorNum) {
                                      f1 *= 0.5;
                                    }
                                    if (_root.lastdev + 2 > _root.floorNum) {
                                      f1 *= 0.5;
                                    }
                                    if ((Math.random() < f1 or satan) && _root.devil != 3 && _root.floorNum != 1 && _root.floorNum < 9) {
                                      _root.devil = 2;
                                      _root.lastdev = _root.floorNum;
                                      if (_root.demonz == 0) {
                                        _root.demonz = 1;
                                      }
                                      if (_root.godRoomFloor) {
                                        if (fra < 30) {
                                          trg.gotoAndStop(41);
                                        } else {
                                          trg.gotoAndStop(40);
                                        }
                                        _root.mmus = _root.soundy('isaacxpholyroomreveal.mp3', 100);
                                      } else {
                                        if (fra < 30) {
                                          trg.gotoAndStop(19);
                                        } else {
                                          trg.gotoAndStop(18);
                                        }
                                      }
                                    } else {
                                      _root.devil = 3;
                                      nohit = true;
                                    }
                                  }
                                } else {
                                  if (trg.boss) {
                                    if (fra < 30) {
                                      trg.gotoAndStop(13);
                                    } else {
                                      trg.gotoAndStop(15);
                                    }
                                  } else {
                                    trg.gotoAndStop(3);
                                    if (fra < 30) {
                                      trg.p.gotoAndStop(trg.p._totalframes);
                                    }
                                  }
                                }
                              }
                            }
                          }
                        }
                      }
                    }
                  }
                  if (trg._visible && !nohit) {
                    v1 = trg.blo;
                    levz[v1] = 0;
                    clevc[v1] = 0;
                    if (trg.cus) {
                      levz[v1] = 0.99;
                    }
                  }
                }
                if (fra > 30 && shutdoor == 0) {
                  if (haveEffect[94] or haveEffect[96] or haveEffect[98] or haveEffect[131]) {
                    f1 = haveEffect[94] + (haveEffect[96] + haveEffect[98] * 2 + haveEffect[131]) * 1.1;
                    _root.monbb += 0.5 / f1;
                  }
                  f1 = itemChargeRates[_root.spacebarItem];
                  if (_root.itemCharges < 1) {
                    _root.itemCharges += 1 / f1;
                    itb = 5;
                    if (_root.itemCharges < 1) {
                      _root.soundy('beep.wav');
                    } else {
                      _root.soundy('itemrecharge.wav');
                    }
                  }
                  if (_root.bossRoom == _root.lev or _root.bossRoom2 == _root.lev) {
                    bosssp();
                    killa = true;
                    if (_root.lev == _root.bossRoom2 && _root.labyrinthCurse) {
                      _root.bossID = _root.bossID2;
                    }
                  } else {
                    if (_root.amusic && !cock) {
                      cock = true;
                      _root.musc.done = true;
                      _root.bossmusic = true;
                    }
                    f1 = Math.random();
                    if (haveEffect[46]) {
                      f1 = f1 * 0.9 + 0.1;
                    }
                    if (_root.luck > 0) {
                      f1 = f1 * 0.9 + 0.1;
                    }
                    if (_root.luck < 0) {		//Negative luck actually boosts room drops!
                      f1 -= _root.luck * 0.1;	//DUMB DUMB DUMB DUMB DUMB
                    }
                    f2 = 0;
                    trinketForcedSpawn(false);
                    if (haveTrinket(42)) {
                      if (haveEffect[46] && _root.luck > 0) {
                        f1 = f1 * 0.98 + 0.02;
                      } else {
                        f1 = f1 * 0.9 + 0.1;
                      }
                    }
                    if (haveEffect[134]) {
                      if (random(3) == 0) {
                        f1 = 1;
                        f2 = 5.05 + random(2) * 0.01;
                      } else {
                        if (random(3) == 0) {
                          f1 = 0;
                        }
                      }
                    }
                    if (haveTrinket(46)) {
                      if (random(10) == 0) {
                        if (player.mhp > 0) {
                          player.hp += 0.5;
                          parc('hearter', player.xp, player.yp - 20, 0, 100, player.dpppp + 5000);
                          _root.soundy('Vamp_Gulp.mp');
                        }
                      }
                    }
                    if (f1 > 0.22) {
                      if (f1 < 0.3) {
                        if (random(3) == 0) {
                          f0 = 5.3;
                        } else {
                          if (random(2) == 0) {
                            f0 = 5.35;
                          } else {
                            f0 = 5.07;
                          }
                        }
                      } else {
                        if (f1 < 0.45) {
                          f0 = 5.02;
                        } else {
                          if (f1 < 0.6) {
                            f0 = 5.01;
                          } else {
                            if (f1 < 0.8 - _root.floorNum * 0.01) {
                              f0 = 5.03;
                            } else {
                              if (f1 < 0.95) {
                                f0 = 5.04;
                              } else {
                                f0 = 5.05;
                              }
                            }
                          }
                        }
                      }
                      if (f2 > 0) {
                        f0 = f2;
                      }
                      spaw(320, 280, 0, f0);
                    }
                  }
                }
              }
              openss = true;
            } else {
              if (!openss) {
                justnow = 0;
              }
            }
          }
        }
        for (e in drawer) {
          drawer[e].clear();
        }
        if (!Key.isDown(80) && !Key.isDown(27)) {
          unspace = true;
        }
        if (_root.unl._currentframe != 1 or _root.over._currentframe != 1) {
          unlo = true;
          unpause = false;
        }
        flyshut = 0;
        if (!unpause) {
          if (unlo) {
            unpause = true;
            unlo = false;
            if ((player.d._currentframe != 4 or player.d.d.d._currentframe > 9) && (player.d._currentframe != 11 or player.d.d.d._currentframe > 9)) {
              scerf();
            }
          } else {
            if (gameover == 0 && _root.hud.paus._currentframe == 1) {
              _root.hud.paus.gotoAndStop(2);
              scerf();
            }
          }
          if (Key.isDown(80) && unspace) {
            unpause = true;
            unspace = false;
          }
          nosp = true;
          _root.hud.paus.st0.gotoAndStop(Math.min(1 + Math.max(1, Math.round((_root.playsp - 0.8) * 4)), 8));
          _root.hud.paus.st1.gotoAndStop(Math.min(Math.max(1, Math.round(12 - _root.fireRate)), 8));
          _root.hud.paus.st2.gotoAndStop(Math.max(1, Math.min(1 + Math.round((_root.tearDamage - 2.4) * 1.1), 8)));
          _root.hud.paus.st3.gotoAndStop(Math.max(1, Math.min(1 + Math.round((_root.tearRange - 20) / 4), 8)));
        } else {
          if (bgg2 != undefined) {
            bgg2 = undefined;
            bggg2.swapDepths(100);
            removeMovieClip(bggg2);
          }
          topz(0);
          --freez;
          --slow;
          --sloww;
          --scare;
          --playsave;
          --unic;
          if (unic < -1) {
            pacman = false;
          }
          if (_root.spacebarItem == 124) {
            if (nofun) {
              nofun = false;
            } else {
              _root.itemCharges += 0.02;
            }
          }
          if (haveEffect[63] && shutdoor != 0 && _root.itemCharges - 0.5 < batteryTimer && _root.itemCharges < 1 && nocharge-- < 0 && _root.lev != _root.arcadeRoom) {
            batteryTimer = Math.min(_root.itemCharges, batteryTimer);
            _root.itemCharges += 0.0004;
            if (hudder != _root.hud.it._currentframe && _root.hud.it._currentframe < 15) {
              if (_root.itemCharges < 1) {
              } else {}
              _root.soundy('batterycharge.mp');
              parc('batter', player.xp, player.yp - 20, 0, 100, player.dpppp + 5000);
            }
          }
          _root.hud.paus.gotoAndStop(1);
          ++fra;
          if (justnow > 10) {
            for (e in door) {
              trg = door[e];
              if ((_root.goldenKey or _root.keys > 0) && enfcheck(trg._x, trg._y, player.xp, player.yp, 60) && keyhole == trg.blo) {
                if (trg.shop or trg.boner2 or trg.boner or trg.lib) {
                  v1 = trg.blo;
                  levz[v1] = 0;
                  clevc[v1] = 0;
                  if (!_root.libraryUnlocked && trg.lib) {
                    trg.gotoAndStop(8);
                    if (!_root.goldenKey) {
                      --_root.keys;
                    }
                    _root.libraryUnlocked = true;
                    _root.soundy('Unlock00.wav', 100);
                  }
                  if (!_root.shopa && trg.shop) {
                    trg.gotoAndStop(8);
                    if (!_root.goldenKey) {
                      --_root.keys;
                    }
                    _root.shopa = true;
                    _root.soundy('Unlock00.wav', 100);
                  }
                  if (!_root.treasureRoomOpened && trg.boner) {
                    trg.gotoAndStop(31);
                    if (!_root.goldenKey) {
                      --_root.keys;
                    }
                    _root.treasureRoomOpened = true;
                    _root.soundy('Unlock00.wav', 100);
                  }
                  if (!_root.treasureRoom2Opened && trg.boner2) {
                    trg.gotoAndStop(31);
                    if (!_root.goldenKey) {
                      --_root.keys;
                    }
                    _root.treasureRoom2Opened = true;
                    _root.soundy('Unlock00.wav', 100);
                  }
                }
              }
              if (trg.arcadeRoom && _root.coins > 0 && enfcheck(trg._x, trg._y, player.xp, player.yp, 60) && keyhole == trg.blo) {
                v1 = trg.blo;
                levz[v1] = 0;
                clevc[v1] = 0;
                if (!_root.payedArcadeFee) {
                  trg.gotoAndStop(22);
                  --_root.coins;
                  _root.payedArcadeFee = true;
                  _root.soundy('Coin_Slot.mp', 100);
                }
              }
            }
          }
          _root.p.gotoAndStop(1);
          if ((Key.isDown(27) or Key.isDown(80)) && unspace) {
            _root.p.gotoAndStop(_root.pinfo);
            unpause = false;
            unspace = false;
          }
          topz(1);
          f0 = fra % 2 + 1;
          for (e in par) {
            trg = par[e];
            if (trg.done) {
              removeMovieClip(par[e]);
              par.splice(e, 1);
            } else {
              if (trg.perm && ashut > 0) {
                trg.stop();
              } else {
                trg.nextFrame();
              }
            }
          }
          actions1();
          if (brr.length > 0) {
            breakall();
            brr = [];
            brr2 = [];
          }
          playc();
          ++decoy;
          if (decoy == 15) {
            decer = bomb(4);
          }
          if (pageantBoyCoins > 0) {
            --pageantBoyCoins;
            spaw(player.xp, player.yp, 40, 5.02);
          }
          if (itemSpawnsPickups.length > 0) {
            spaw(player.xp, player.yp, 40, itemSpawnsPickups.pop());
          }
          if (portableSlot != undefined) {
            --portableSlot;
            if (portableSlot < 0) {
              f2 = 0;
              f12 = 1;
              slotPrizes(rollSlots());
              if (f2 > 0) {
                if (f2 < 7) {
                  emo();
                }
                if (f1 < 33) {
                  _root.soundy('slotspawn' + random(3) + '.wav');
                }
                i = 0;
                while (i < f12) {
                  var trg2 = spaw(player.xp, player.yp, 40, f2);
                  ++i;
                }
              }
              portableSlot = undefined;
            }
          }
          topz(2);
          physix();
          tip(2);
          v = 0.7;
          if (fra % 1000 == 999) {
            f1 = new Array();
            for (e in levz) {
              f1[e] = levz[e];
            }
            levz = new Array(f1.length);
            for (e in f1) {
              levz[e] = f1[e];
            }
          }
          v1 = _root.tex;
          _root.tex = ' ';
          e = 0;
          while (e < alltimer.length) {
            alltimer[e] *= 0.96;
            _root.tex += ' - ' + Math.round(alltimer[e] * 100) / 100;
            ++e;
          }
          f1 = getTimer();
          if (fra > 35 or _root.lev != 35) {
            wtfps *= 0.9;
            wtfps += Math.max(1, (1000 / (f1 - wtfps2)) * 0.1);
          }
          qqua = _root.so.data.qqal == 'AUTO' or _root.so.data.qqal == undefined;
          if (qqua) {
            if (wtfps < 14) {
              if (_quality == 'MEDIUM') {
                _quality = 'LOW';
              }
            }
            if (wtfps < 26) {
              if (_quality == 'HIGH') {
                _quality = 'MEDIUM';
              }
            }
            if (wtfps > 29.4 && _quality == 'MEDIUM' or wtfps > 25 && _quality == 'LOW') {
              if (wtff++ > 100) {
                wtff = 0;
                if (_quality == 'MEDIUM') {
                  _quality = 'HIGH';
                } else {
                  if (_quality == 'LOW') {
                    _quality = 'MEDIUM';
                  }
                }
              }
            } else {
              wtff = 0;
            }
          }
          wtfps2 = f1;
          _root.tex = _quality + ' fps:' + Math.round(wtfps) + '  ' + _root.tex + '\nf:' + Math.round(_root.fireRate) + ' d:' + Math.round(_root.tearDamage * 10) / 10 + ' r:' + Math.round(_root.tearRange * 10) / 10 + ' ' + ingrid(player.xp, player.yp) + ' ' + _root.rarer[_root.lev];
          _root.tex = _root.tex + '\n' + v1;
          if (chestopen != undefined) {
            trg = chestopen;
            chestopen = undefined;
            if (trg != 2) {
              chestox = trg.xp;
              chestoy = trg.yp;
            }
            if (!trg.empty) {
              if (arenaActive == 1 && _root.lev == _root.arenaRoom) {
                arenaActive = 2;
              }
              trg.empty = true;
              if (trg.col == 31) { //Demon Beggar
                boil(false);
                boil(true);
              } else {
                if (trg.c2) { //Red Chest
                  f10 = 2;
                  f1 = [81, 134, 133, 145];
                  if (_root.SecretUnlocked[79]) {
                    f1.push(134);
                  }
                  f1 = f1[random(f1.length)];
                  if (!haveEffect[f1] && random(10) == 0) {
                    var trg2 = create(chestox, chestoy, 0, 0, 0, 0, 5.1);
                    trg2.alt = true;
                    trg2.fra -= 15;
                    trg.done = true;
                    trg2.alt = 5;
                    trg2.it = f1;
                    f1 = 70;
                    enf = enfcheck(chestox, chestoy, player.xp, player.yp, f1);
                    if (enf < f1) {
                      enf = ((f1 - enf) / enf) * 0.4;
                      player.xbew -= xenf * enf;
                      player.ybew -= yenf * enf;
                    }
                  } else {
                    if (random(18) == 0) { //Teleport to Devil Room
                      teleportTarget = 166;
                      teleport();
                    } else {
                      if (random(5) == 0) { //Spiders
                        boil(false);
                        boil(true);
                      } else {
                        if (random(5) == 0) { //Super Troll Bombs
                          spaw(trg.xp, trg.yp, 20, 5.040000005);
                        } else {
                          if (random(5) == 0) { //Blue Flies
                            blueFlies += 3;
                          } else {
                            f1 = [5.010000003, 5.040000003, 5.07]; //Soul Hearts, Troll Bombs, Pills
                            f1 = f1[random(f1.length)];
                            if (f1 == 5.010000003 && random(2) == 0) {
                              cspawn(f1, 1);
                            } else {
                              cspawn(f1, 2);
                            }
                          }
                        }
                      }
                    }
                  }
                } else {
                  if (trg.d._currentframe == 8 && trg.col == 1) { //Blood Donation Machines
                    f10 = 1 + random(2);
                  } else {
                    if (trg.d._currentframe == 6) {
                      f10 = Math.max(2, random(8) - 1); //Gold chests and stuff drop 2-6 pickups.
                    } else {
                      f10 = Math.max(2, random(4) - 1); //Regular chests and stuff drop 2 pickups.
                    }
                  }
                  f2 = 0;
                  if (random(3) != 0) {
                    trinketForcedSpawn(true);			//Trinket spawners have a 1 in 3 chance.
                    if (haveTrinket(42) or f2 > 0) { 	//Lucky Toe spawns extra item, as well as trinket spawners.
                      ++f10;
                    }
                  }
                  if (trg.goldPoop) { //Golden Poop
                    if (random(3) == 0 && _root.SecretUnlocked[84] && !_root.fakePennyDrop) {
                      _root.fakePennyDrop = true;
                      create(trg.xp, trg.yp, 0, 0, 0, 0, 5.35);
                    } else {
                      cspawn(5.02, 5 + random(3)); //Spawn 5-7 coins
                    }
                  } else {
                    z = 0;
                    for (;;) {
                      if (!(z < f10 && !trg.done)) break;
                      f12 = 1;
                      f1 = Math.random();
                      if (f2 > 0) {
                        f0 = f2;
                        f2 = 0;
                      } else {
                        if ((_root.SecretUnlocked[18] && random(10) == 0 && trg == 2 or random(5) == 0 && trg.d._currentframe == 6) && z == 0 && (trg != 2 or !haveEffect[90]) or _root.floorNum == 11) {
                          f1 = 70;
                          enf = enfcheck(chestox, chestoy, player.xp, player.yp, f1);
                          if (enf < f1) {
                            enf = ((f1 - enf) / enf) * 0.4;
                            player.xbew -= xenf * enf;
                            player.ybew -= yenf * enf;
                          }
                          f0 = 5.1;
                          trg.done = true;
                          treas = true;
                        } else {
                          if (random(5) == 0 && z == 0 && trg != 2) {
                            f1 = 70;
                            enf = enfcheck(chestox, chestoy, player.xp, player.yp, f1);
                            if (enf < f1) {
                              enf = ((f1 - enf) / enf) * 0.4;
                              player.xbew -= xenf * enf;
                              player.ybew -= yenf * enf;
                            }
                            if (trg.d._currentframe == 6) {
                              f0 = 5.3;
                            } else {
                              f0 = 5.07;
                            }
                            if (random(2) == 0) {
                              f0 = 5.35;
                            }
                            f10 = -100;
                          } else {
                            if (f1 < 0.35 && trg != 2) {
                              f0 = 5.02;
                              f12 = random(3) + 1;
                            } else {
                              if (f1 < 0.55 or f1 < 0.6 && trg == 2) {
                                f0 = 5;
                                if (random(2) == 0) {
                                  --f10;
                                }
                              } else {
                                if (f1 < 0.7) {
                                  f0 = 5.03;
                                  if (trg == 2) {
                                    f10 = -100;
                                  }
                                } else {
                                  if (f1 < 0.71 && z == 0) {
                                    f0 = 5.05;
                                    f10 = -100;
                                  } else {
                                    if ((f1 < 0.72 or trg == 2 && f1 < 0.9) && z == 0) {
                                      f0 = 5.06;
                                      f10 = -100;
                                    } else {
                                      f0 = 5.04;
                                    }
                                  }
                                }
                              }
                            }
                          }
                        }
                      }
                      if (trg.d._currentframe == 8 && trg.col == 1) { //Blood Donation Machines
                        if (random(2) == 0) {
                          f0 = 5.02;
                          f12 = random(4) + 1;
                        } else {
                          f0 = 5;
                        }
                      }
                      cspawn(f0, f12);
                      ++z;
                    }
                  }
                }
              }
              treas = false;
            }
          }
          tip(0);
        }
        for (e in ball) {
          trg = ball[e];
          if (trg.s == 4) {
            if (trg.d._currentframe == 3 && haveEffect[140]) {
              trg.dfr = true;
              trg.d.gotoAndStop(5);
            }
          }
          if (trg.alter) {
            f1 = trg.alter;
            if (trg.s == 16) {
              trg.d.hx.d.gotoAndStop(f1);
              trg.d.d.hx.d.gotoAndStop(f1);
              trg.d.d.d.hx.d.gotoAndStop(f1);
            } else {
              if (trg.s == 46 && trg.alter == 3 && trg.minb == 3) {
                trg.d.he.gotoAndStop(f1);
                trg.d.d.he.gotoAndStop(f1);
                trg.d.d.d.he.gotoAndStop(f1);
              }
              trg.d.hx.gotoAndStop(f1);
              trg.d.d.hx.gotoAndStop(f1);
              trg.d.d.d.hx.gotoAndStop(f1);
              trg.d.d.d.d.hx.gotoAndStop(f1);
              if (trg.s == 50) {
                trg.d.d.hx.h.gotoAndStop(trg.f3);
              }
              if (trg.s == 60) {
                if (trg.d._currentframe == 5) {
                  trg.d.d.gotoAndStop(f1);
                }
                trg.d.hxx.gotoAndStop(f1);
                trg.d.d.hxx.gotoAndStop(f1);
                trg.d.d.d.hxx.gotoAndStop(f1);
              }
            }
          }
        }
        if (fra % 50 == 0) {
          f1 = [];
          f2 = [];
          a = 0;
          while (a < ball.length) {
            f1[a] = ball[a];
            ++a;
          }
          a = 0;
          while (a < par.length) {
            f2[a] = par[a];
            ++a;
          }
          ball = new Array(f1.length);
          par = new Array(f2.length);
          a = 0;
          while (a < ball.length) {
            ball[a] = f1[a];
            ++a;
          }
          a = 0;
          while (a < par.length) {
            par[a] = f2[a];
            ++a;
          }
        }
        if (wtftex) {
          _root.tex = wtftex;
        }
        trg = player;
        if (trg.d._currentframe != 1) {
          if (trg.d._currentframe == 7 or trg.d._currentframe == 8) {
            trgnextd();
          } else {
            trg.d.d.gotoAndStop(sk);
            if (bgg2 == undefined) {
              if (trgnextd(trg.d.d.d, true) && trg.d._currentframe != 6) {
                playfirst = true;
              }
            }
            if (trg.d.d.d._currentframe == 32 && trg.d._currentframe == 6) {
              _root.soundy('isaacdies.wav');
              if (gameover <= 0) {
                gameover = 1;
              }
            }
          }
        } else {
          if (demon > 0) {
            sk = 7;
          }
        }
        trg.d.d.d.it.d.gotoAndStop(trg.it);
        trg.d.d.d.it.d.p.gotoAndStop(player.pillItem);
        trg.d.d.d.it.d._yscale = 10000 / player._xscale;
        trg.d.d.d.it.d._xscale = trg.d.d.d.it.d._yscale;
        trg.d.hs._visible = (trg.d.bo._currentframe == 16 or trg.d.bo._currentframe == 17 or trg.d.bo._currentframe == 18) && trg.d.bo.d._currentframe != 2;
        if (trg.d.hs._visible) {
          if (trg.d.bo.d._currentframe == 1) {
            trg.d.hs.gotoAndStop(1);
          } else {
            trg.d.hs.gotoAndStop(2);
          }
          trg.d.hs._xscale = trg.d.bo._xscale;
        }
        if (fra > 2 && fra < 15) {
          player._visible = true;
        }
        if (plxxx > 0) {
          player.fire = 1000;
          player.xp = plxxx;
          player.yp = plyyx;
          player.xbew = 0;
          player.ybew = 0;
        }
        for (e in ball) {
          trg = ball[e];
          if (trg.s == 42) {
            trg.xp = trg.xpp;
            trg.yp = trg.ypp;
            trg.xbew = 0;
            trg.ybew = 0;
          }
        }
        trg = player;
        if (trg.d._currentframe == 1 or _root.bombnext) {
          f2 = facer;
          if (trg.d._currentframe == 1) {
            trg.d.d.d.gotoAndStop(f2);
            if (f2 == 17 or f2 == 31) {
              f0 = Math.round((fra - chaf) / 8);
              if (plox <= 8 && chaf == undefined) {
                f0 = 0;
                if (f2 == 31) {
                  trg.d.d.d.gotoAndStop(33);
                } else {
                  trg.d.d.d.gotoAndStop(1);
                }
                plo = 1;
              } else {
                chaaf = Math.max(1, Math.min(6, f0));
              }
            }
            z = 0;
            while (z < 6) {
              f4 = false;
              trg2 = trg.d.d.d['hat' + z];
              f3 = _root.hatmode[z];
              if (_root.colit == 86 && z == 0) {
                f3 = 18;
              }
              if (_root.pickedUp[161] && z == 0) {
              }
              if (z == 4) {
                if (haveEffect[117]) {
                  f3 = 38;
                }
                if (bra && freez > 0) {
                  f3 = 28;
                }
              }
              if (_root.pickedUp[152] && z == 4) {
                f3 = 45;
                f4 = true;
                trg2.d.gotoAndStop(9);
              }
              if (f3 > 0 && !nohat) {
                trg2.gotoAndStop(f3);
                trg2.d.stop();
                if (z != 0) {
                  trg2._x = trg.d.d.d.hat0._x;
                  trg2._y = trg.d.d.d.hat0._y;
                }
                if (trg2.d._totalframes > 4 && plox > 8) {
                  trg2.d.gotoAndStop(plo + 4);
                } else {
                  trg2.d.gotoAndStop(plo);
                }
              } else {
                trg2.gotoAndStop(1);
              }
              if (f4) {
                trg2 = trg2.d.l;
                if (trg.lfrr - fra > -3) {
                  lass = trg.lass;
                  if (Math.abs(trg.xpp) > Math.abs(trg.ypp)) {
                    f1 = (lass / trg.d.d._xscale / trg._xscale) * 10000 + (trg2._x - 6) * trg.xpp - 13;
                  } else {
                    f1 = (lass / trg.d.d._xscale / trg._xscale) * 10000 + (trg2._y + 20) * trg.ypp;
                  }
                  trg2.gotoAndStop(fra % 3 + 1);
                  trg2._yscale = f1;
                  trg2 = undefined;
                } else {
                  trg2._visible = false;
                }
              }
              ++z;
            }
          }
        }
      }

      llev = [2, 114, 57, 175, 2, 113, 60, 167, 2, 101, 53, 152, 2, 90, 46, 135, 2, 80, 0, 0, 6, 34];
      llev2 = [2, 116, 57, 176, 2, 115, 60, 168, 2, 103, 53, 153, 2, 91, 46, 135, 2, 90, 0, 0, 6, 34];
      specol = [[1, 0.1, 0.1], [0.5, 0.5, 0], [0.2, 0.5, 0.4], [1, 0.5, 0.5], [0.7, 0.45, 0.4], [0.1, 0.8, 0.2], [0.1, 1, 0.5], [0, 0.15, 0.15], [0.55, 0.55, 1.35], [1.6, 0.7, 1]];
      specol2 = [0, [1, 0.6, 0.6], [0.6, 0.6, 0.6], [0.6, 1, 0.6], [0.6, 1, 1], [0.5, 0.7, 0.5], [1, 0.7, 0.5], [0.5, 0.7, 1], [0.5, 0.7, 0.7], [1, 0.7, 0.5], [0, 1.7, 1.1], [0.6, 0.7, 0.6], [1, 1, 0.5], [0.3, 0.7, 0.6], [1, 0.6, 0.6], [0.5, 0.5, 0.6], [0.44, 0.44, 0.44], [0.5, 0.5, 0.5, 50, 50, 50], [0.24, 0.24, 0.24], [1.2, 0.7, 0.7], [2.5, 1.2, 1.5], [1, 1, 1, 20, -50, -222], [1.5, 1, 1.15]];
      levelNames = [0, 'Basement 1', 'Basement 2', 'Caves 1', 'Caves 2', 'The Depths 1', 'The Depths 2', 'The Womb 1', 'The Womb 2', 'Sheol', 0, 'The Chest'];
      alternateLevelNames = [0, 'Cellar 1', 'Cellar 2', 'Catacombs 1', 'Catacombs 2', 'Necropolis 1', 'Necropolis 2', 'Utero 1', 'Utero 2', 'Cathedral', 0, 'The Chest'];
      _root.tex = undefined;
      if (_root.challenge <= 0) {
        _root.challenge = 0;
      }
      if (_root.lev == _root.bossRoom2) {
        altboss = _root.altboss2;
      }
      if (_root.lev == _root.bossRoom) {
        altboss = _root.altboss;
        if (_root.floorNum == 8 or _root.floorNum == 6 && !_root.SecretUnlocked[3]) {
          _root.unl.gotoAndStop(1);
          _root.unl.nogo = true;
        }
      }
      gridx = 0;
      gridy = 0;
      if (_root._xscale < 110) {
        gridxs = 640;
        gridys = 480;
        hdx = 1;
      } else {
        if (_root._xscale < 135) {
          gridxs = 800;
          gridys = 620;
          hdd = true;
          hdx = 1.25;
        } else {
          gridxs = 1100;
          gridys = 800;
          hdd = true;
          hdx = 1.667;
        }
      }
      gridv = 100;
      gridmax = 10;
      tiles._visible = false;
      razor = 0;
      rage = 1;
      rag = 1;
      if (_root.levz.length <= 1) { //This all happens when you first enter a floor.
        f1 = getTimer() % 100;
        e = 0;
        while (e < f1) {
          f2 = random(random(10)) * Math.random(); //WHAT IN GOD'S NAME
          ++e;
        }
        _root.darky(120);
        if (_root.newstartt or _root.spacebarItem == undefined) {
          _root.newstartt = false;
          newstats();
          _root.eternalHeart = false;
        }
        _root.lostCurse = false;
        _root.darknessCurse = false;
        f1 = 80;
        if (_root.SecretUnlocked[4]) {
          f1 = 30;
        }
        if (_root.SecretUnlocked[42]) {
          f1 = 10;
        }
        if (_root.SecretUnlocked[65] or _root.SecretUnlocked[66] or _root.SecretUnlocked[67] or _root.SecretUnlocked[68] or _root.SecretUnlocked[70] or _root.SecretUnlocked[69] or _root.SecretUnlocked[72]) {
          f1 = 5;
        }
        checkTreasureSkip();
        _root.superSin = random(f1) == 0 && _root.floorNum != 1 && (_root.floorNum != 2 or !_root.labyrinthCurse);
        _root.lostCurse = false;
        _root.labyrinthCurse = false;
        _root.darknessCurse = false;
        if (_root.floorNum == 11) {
        } else {
          if (random(f1) == 0 && _root.floorNum % 2 == 1 && _root.floorNum < 8) {
            _root.labyrinthCurse = true;
          } else {
            _root.labyrinthCurse = false;
            if (random(f1 * 2) == 0) {
              _root.lostCurse = true;
            } else {
              if (random(f1 * 2) == 0) {
                _root.darknessCurse = true;
              }
            }
          }
        }
        if (_root.challenge == 1) {
          _root.lostCurse = false;
          _root.labyrinthCurse = false;
          _root.darknessCurse = true;
        }
        if (_root.challenge == 3) {
          _root.lostCurse = false;
          _root.labyrinthCurse = true;
          _root.darknessCurse = false;
        }
        if (_root.labyrinthCurse) {
          ++_root.floorNum;
          curss = 'Curse of the Labyrinth';
        } else {
          if (_root.lostCurse) {
            curss = 'Curse of the Lost';
          } else {
            if (_root.darknessCurse) {
              curss = 'Curse of Darkness';
            }
          }
        }
        _root.rax00 = random(5);
        _root.rax01 = random(5);
        _root.rax02 = random(5);
        _root.rax03 = random(5);
        _root.rax04 = random(5);
        _root.rax10 = random(5);
        _root.rax11 = random(5);
        _root.rax12 = random(5);
        _root.rax13 = random(5);
        _root.rax14 = random(5);
        _root.rax20 = random(5);
        _root.rax21 = random(5);
        _root.rax22 = random(5);
        _root.rax23 = random(5);
        _root.rax24 = random(5);
        _root.goldenKey = false;
        _root.mapsize = 0;
        f6 = Math.min(20, random(2) + 5 + _root.floorNum * 2.6);
        _root.rarer = [];
        _root.levblow = [];
        _root.levsav = [];
        _root.levit = [];
        _root.beenlev = [];
        _root.beenlev2 = [];
        _root.seenRoom = [];
        _root.bomf = [];
        _root.shopa = false;
        _root.libraryUnlocked = false;
        _root.treasureRoomOpened = _root.floorNum == 1;
        _root.treasureRoom2Opened = false;
        _root.foundSecretRoom = false;
        _root.foundSecretRoom2 = false;
        _root.secretRoom2Type = random(5);
        _root.minibossKnown = false;
        _root.payedArcadeFee = false;
        _root.seenArcade = false;
        _root.chambb = false;
        _root.arenaActive = false;
        _root.shopaz = false;
        _root.bossd = false;
        _root.treasd = false;
        _root.treasd2 = false;
        _root.visitedArcade = false;
        _root.levcol = [];
        _root.world = false;
        _root.godRoomFloor = random(2) == 0 && _root.devilDeals == 0 && _root.lastdev > 0;
        _root.itemChargeTable = [1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1, 1];
        _root.devil = _root.floorNum != 1;
        _root.beggarKilled = false;
        _root.bossArena = _root.floorNum % 2 == 0 && random(2) == 0;
        _root.cainsEye = false;
        if (haveTrinket(59) && random(4) == 0) {
          haveEffect[21] = true;
          _root.cainsEye = haveEffect[21];
        }
        _root.altchap = 0;
        if (random(2) == 0 && _root.floorNum < 9 or _root.heaven == 2) {
          _root.altchap = 9;
        }
        fuckup = 0;
        if (_root.floorNum == 1 or _root.floorNum == 3 or _root.floorNum == 5 or _root.floorNum == 7) {
          _root.nodmg = true;
        }
        if (_root.hairball > 1) {
          _root.hairball = Math.round(_root.hairball * 0.5 + 0.5);
        } else {
          _root.hairball = 1;
        }
        if (_root.labyrinthCurse) {
          f6 *= 1.8;
          f6 = Math.min(45, f6);
        } else {
          if (_root.lostCurse) {
            f6 += 4;
          }
        }
        for (;;) {
          if (!((_root.mapsize < f6 or _root.levz.length <= 1 or _root.bossRoom == 45 or _root.secretRoom == undefined && _root.floorNum < 3 or _root.bossRoom == 25 or _root.bossRoom == 36 or _root.bossRoom == 34) && fuckup++ < 1000)) break;
          endrooms = [];
          _root.levz = new Array(80);
          e = 0;
          while (e < 80) {
            _root.levz[e] = 0;
            ++e;
          }
          acts = [];
          acts2 = [];
          pffx(35);
          f3 = random(4);
          f5 = 0;
          if (_root.labyrinthCurse) {
            f6 -= 1;
          }
          v3 = 0;
          e = 0;
          while (e < 300) {
            acts2[acts2.length] = 0;
            acts = acts2.slice(0, -1);
            acts2 = [];
            if (f6 > 15) {
              pffx(35);
            }
            for (a in acts) {
              v1 = acts[a];
              if (v1 > 0) {
                v3 = v1;
              }
              f8 = 0;
              if (random(2) == 0 && v1 % 10 < 9) {
                pffx(v1 + 1);
              }
              if (random(2) == 0 && v1 % 10 > 1) {
                pffx(v1 - 1);
              }
              if (random(2) == 0 && v1 < 70) {
                pffx(v1 + 10);
              }
              if (random(2) == 0 && v1 > 10) {
                pffx(v1 - 10);
              }
              if (f8 == 0 && v1 != 35) {
                endrooms.push(v1);
              }
            }
            if (acts2.length < 2) {
              e -= 0.5;
            }
            ++e;
          }
          if (_root.labyrinthCurse) {
            f6 += 1;
          }
          _root.lastl = _root.lev;
          _root.lev = 35;
          _root.lastl = 35;
          _root.mapsize = f5;
          _root.bossRoom = endrooms[endrooms.length - 1];
          _root.shopl = _root.bossRoom;
          _root.boner = _root.bossRoom;
          endrooms.splice(endrooms.length - 1, 1);
          if (_root.labyrinthCurse) {
            f1 = -1;
            if (ncheck(_root.bossRoom + 1) == 1 && _root.bossRoom % 10 < 9) {
              f1 = _root.bossRoom + 1;
            }
            if (ncheck(_root.bossRoom - 1) == 1 && _root.bossRoom % 10 > 1) {
              f1 = _root.bossRoom - 1;
            }
            if (ncheck(_root.bossRoom + 10) == 1 && _root.bosslv1 < 70) {
              f1 = _root.bossRoom + 10;
            }
            if (ncheck(_root.bossRoom - 10) == 1 && _root.bossRoom > 10) {
              f1 = _root.bossRoom - 10;
            }
            if (f1 > 0) {
              _root.bossRoom2 = _root.bossRoom;
              _root.bossRoom = f1;
            } else {
              _root.bossRoom = 34;
            }
          } else {
            _root.bossRoom2 = undefined;
          }
          _root.secretRoom = undefined;
          _root.secretRoom2 = undefined;
          _root.beenlev = [];
          _root.secretRoom2 = ender();
          if (_root.mapsize * 2 > f6 && _root.bossRoom != 34) {
            if (_root.labyrinthCurse) {
              endrooms.splice(0, Math.max(0, endrooms.length - 6));
            }
            e = 0;
            while (e < 3000) {
              f1 = random(_root.levz.length);
              f2 = f1 % 10;
              if (!_root.levz[f1] && f2 < 9 && f2 > 1) {
                f2 = ncheck(f1);
                f4 = true;
                if (f2 > 0) {
                  f3 = ncheck1(f1);
                  if (_root.labyrinthCurse) {
                  } else {}
                } else {
                  f3 = false;
                }
                if ((f2 > 2 && f3 or (f2 > 2 or f2 > 1.9 && (e > 600 or f3)) && e > 300 && f4) && _root.secretRoom == undefined) {
                  _root.levz[f1] = 'hide' + random(5);
                  _root.secretRoom = f1;
                }
                if (_root.mapsize < f6 + 1 && _root.labyrinthCurse && f1 != _root.secretRoom) {
                  if (f3 && (f2 > 1 or f2 == 1 && random(2) == 0)) {
                    _root.levz[f1] = 0.75;
                    ++_root.mapsize;
                  }
                } else {
                  if (_root.secretRoom != undefined) {
                    e += 100000;
                  }
                }
              }
              ++e;
            }
          }
          _root.minibossRoom = undefined;
          _root.arcadeRoom = undefined;
          _root.arenaRoom = undefined;
          _root.sacRoomRevealed = undefined;
          _root.librarySeen = undefined;
          _root.seenCurseRoom = undefined;
          _root.curseRoom = undefined;
          _root.sacrificeRoom = undefined;
          _root.successSacrifice = false;
          _root.libraryRoom = undefined;
          _root.boner2 = undefined;
          _root.boner = _root.boner2;
          if ((endrooms.length >= 4 or _root.floorNum == 1 && endrooms.length >= 3) && _root.bossRoom != _root.lev && _root.bossRoom > 0) {
            if (_root.floorNum != 11) {
              _root.shopl = ender();
              if (_root.challenge < 5 && (_root.challenge != 2 or random(3) != 1)) {
                _root.boner = ender();
              }
              if (_root.labyrinthCurse && _root.challenge < 5) {
                _root.boner2 = ender();
              }
              if (endrooms.length > 0 && (random(7) == 0 or random(4) == 0 && _root.fullhp)) {
                _root.sacrificeRoom = ender();
              }
              if (endrooms.length > 0 && (random(20) == 0 or _root.carryingBook && random(4) == 0)) {
                _root.libraryRoom = ender();
              }
              if (endrooms.length > 0 && (random(2) == 0 or _root.lastdev && random(4) == 0)) {
                _root.curseRoom = ender();
              }
              if (endrooms.length > 0 && (random(4) == 0 or _root.floorNum == 1 && random(3) == 0) && _root.minibossPool.length > 0) {
                _root.minibossRoom = ender();
              }
              if (endrooms.length > 0 && _root.fullhp && _root.floorNum > 1 && (random(2) == 0 or _root.floorNum > 2)) {
                _root.arenaRoom = ender();
              }
              if (endrooms.length > 0 && _root.coins >= 5 && _root.floorNum % 2 == 0) {
                _root.arcadeRoom = ender();
              }
            }
          } else {
            _root.levz = [];
            _root.mapsize = 0;
          }
          if (_root.floorNum > 6) {
            _root.boner = undefined;
            _root.boner2 = undefined;
            _root.shopl = undefined;
          }
        }
        if (fuckup >= 399) {
          _root.levz = undefined;
          if (_root.labyrinthCurse) {
            --_root.floorNum;
          }
          _root.cuts = true;
          moveon();
          _root.gotoAndStop('reset');
        }
        f13 = Math.min(llev.length - 2, _root.floorNum * 2 - 2);	//0 2 4 6 8 10 12 14 16 20
        f15 = Math.min(llev.length - 2, _root.floorNum * 2 - 4);	//  0   4    8    12
        f14 = true;
        for (e in _root.levz) {
          if (random(2) == 0 && _root.labyrinthCurse) {
            f14 = f15;
          } else {
            f14 = f13;
          }
          if (_root.levz[e] > 0) {
            if (_root.altchap) {
              _root.levz[e] = random(llev2[f14 + 1] - llev2[f14]) + llev2[f14] + 2;
            } else {
              _root.levz[e] = random(llev[f14 + 1] - llev[f14]) + llev[f14] + 2;
            }
            _root.rarer[e] = random(115) + 65;
          }
        }
        if (_root.labyrinthCurse) {
          --_root.floorNum;
        }
        bosschoose();
        if (_root.labyrinthCurse) {
          _root.levz[_root.bossRoom2] = f1;
          _root.bossID2 = _root.bossID;
          _root.altboss2 = _root.altboss;
          ++_root.floorNum;
          while (_root.bossID2 == _root.bossID) {
            bosschoose();
          }
          _root.levz[_root.bossRoom] = f1;
          f1 = _root.bossID2;
          _root.bossID2 = _root.bossID;
          _root.bossID = f1;
        } else {
          _root.levz[_root.bossRoom] = f1;
        }
        _root.levz[35] = 2;
        _root.levz[166] = 'satan';
        if (_root.godRoomFloor) {
          _root.levz[166] = 'sata';
        } else {
          if (!_root.krampusFought && (random(10) == 0 or random(3) == 0 && _root.devilDeals > 0)) {
            _root.levz[166] = 'krampus';
            _root.krampusFought = _root.floorNum;
          }
        }
        if (_root.floorNum == 8) {
          _root.levz[166] = 'satan1';
        }
        if (_root.floorNum < 9) {
          _root.levz[169] = 'error' + random(4);
        }
        _root.levz[_root.shopl] = 'shop' + (random(6) + 1) * 1;
        _root.levz[_root.sacrificeRoom] = 'sac';
        _root.levz[_root.libraryRoom] = 'lib';
        _root.levz[_root.curseRoom] = 'c';
        _root.levz[_root.secretRoom2] = 'hi' + _root.secretRoom2Type;
        if (random(3) == 0) {
          _root.levz[_root.curseRoom] = 'c' + random(2);
          if (random(4) == 0) {
            _root.levz[_root.curseRoom] = 'c2';
          }
        }
        _root.levz[_root.boner] = 't' + random(6);
        _root.levz[_root.boner2] = 't' + random(6);
        f1 = random(_root.minibossPool.length);
        f2 = 'min';
        if (_root.superSin) {
          f2 = 'mi';
        }
        f3 = f2;
        f2 += _root.minibossPool[f1];
        if (_root.floorNum > 2 && !_root.ultraPride && random(10) == 0) {
          f2 = 'ultraPride';
          _root.ultraPride = true;
        }
        _root.levz[_root.minibossRoom] = f2;
        _root.levz[_root.arcadeRoom] = 'gam' + random(6);
        _root.levz[_root.arenaRoom] = 'cha' + random(6);
        if (_root.floorNum == 11) {
          _root.levz[35] = 5;
        }
        if (_root.bossArena) {
          _root.levz[_root.arenaRoom] = 'cha5';
        }
        if (_root.floorNum > 3 && _root.minibossRoom == undefined) { //GREED
          if (_root.floorNum > 4) { //Greed can't show up in the Secret Room until the Depths
            if (random(3) == 0 && _root.floorNum - 1 > _root.lastGreedFloor) {
              _root.levz[_root.secretRoom] = f3 + 4;
              _root.minibossRoom = _root.secretRoom;
            }
          }
          if (_root.levz[_root.secretRoom] == f3 + 4) {
            _root.lastGreedFloor = _root.floorNum;
          }
          if (random(6 - Math.min(_root.floorNum, 5)) == 0 && _root.floorNum - 1 > _root.lastGreedFloor) {
            _root.minibossRoom = _root.shopl;
            _root.levz[_root.shopl] = f3 + 4;
            _root.lastGreedFloor = _root.floorNum;
          }
        }
        _root.minibossPool.splice(f1, 1);
        if (_root.eternalHeart) {
          _root.over.gotoAndStop(16);
          _root.eternalHeart = false;
          ++_root.hp;
          ++haveEffect[22];
          ++_root.pickedUp[22];
        }
        if (haveTrinket(55)) {
          giveEternalHeart();
        }
      }
      _root.amusic = false;
      if (!_root.beenlev[_root.lev]) {
        if (_root.lev == _root.boner or _root.lev == _root.boner2) {
          _root.mmus = _root.soundy('treasure room enter.mp', 100);
        } else {
          if (_root.lev == _root.bossRoom or _root.lev == _root.bossRoom2) {
            _root.soundy('castleportcullis.wav', 100);
          } else {
            if (_root.lev == _root.arenaRoom) {
              _root.mmus = _root.soundy('weapon room.mp', 100);
            } else {
              if (_root.lev == 166) {
                if (_root.krampusFought == _root.floorNum) {
                  _root.bossmusic = true;
                  _root.soundy('bossintro.mp3');
                } else {
                  _root.mmus = _root.soundy('Satan find.mp', 100);
                }
              } else {
                if (_root.lev == _root.minibossRoom) {
                  _root.mmus = _root.soundy('miniboss.mp', 100);
                  _root.amusic = true;
                  _root.fade = true;
                }
              }
            }
          }
        }
      }
      beenHere = _root.beenlev[_root.lev];
      if (beenHere != 2) {
        _root.beenlev[_root.lev] = true;
      }
      if (_root.lev == _root.secretRoom) {
        revealSecretRoom();
      }
      if (_root.lev == _root.secretRoom2) {
        revealSecretRoom2();
      }
      if (_root.lev == _root.minibossRoom) {
        _root.minibossKnown = true;
      }
      if (_root.lev == _root.arcadeRoom) {
        _root.seenArcade = true;
        _root.payedArcadeFee = true;
        if (!_root.visitedArcade) {
          _root.visitedArcade = true;
          ++_root.so.data.arcadesVisited;
          if (_root.so.data.arcadesVisited > 10) {
            _root.SecretUnlocked[33] = true;
          }
        }
      }
      _root.seenRoom[_root.lev] = true;
      door = [d1, d2, d3, d4];
      v1 = _root.lev;
      if (v1 % 10 < 9) {
        door[2].gol = v1 + 1;
      }
      if (v1 % 10 > 1) {
        door[0].gol = v1 - 1;
      }
      if (v1 < 70) {
        door[1].gol = v1 + 10;
      }
      if (v1 > 10) {
        door[3].gol = v1 - 10;
      }
      for (e in door) {
        trg = door[e];
        trg.swapDepths(int(291 + e));
        if (trg.gol > -1 && _root.levz[trg.gol] != 0) {
        } else {
          trg._visible = false;
        }
      }
      rowz = 16;
      roxx = 40;
      roxx2 = roxx / 2;
      f1 = _root.levz[_root.lev];
      if (f1 == 2) {
        gotoAndStop(2);
      } else {
        if (f1 * 1 > 1) {
          if (_root.floorNum == 11) {
            f15 = 15;
          } else {
            f15 = Math.round(_root.floorNum / 2 + _root.altchap);
          }
          gotoAndStop('levs' + f15);
          inl.gotoAndStop(f1 - 2);
        } else {
          gotoAndStop('levs6');
          inl.gotoAndStop(f1);
          inl.shop.swapDepths(33901);
          inem = true;
        }
      }
      error = false;
      if (_root.lev == _root.arenaRoom) {
        f1 = 19;
      } else {
        if (_root.lev == _root.arcadeRoom) {
          f1 = 15;
        } else {
          if (_root.lev == 166 or _root.lev == _root.curseRoom) {
            f1 = 19;
            if (_root.lev == 166) {
              satan = true;
              _root.devil = 2;
              if (_root.door <= -1) {
                _root.door = random(4);
              }
              if (_root.godRoomFloor) {
                f1 = 26;
              }
            }
          } else {
            if (_root.lev == 169) {
              error = true;
              f1 = 40;
            } else {
              if (_root.floorNum > 8) {
                if (_root.altchap) {
                  f1 = 26;
                } else {
                  f1 = 45;
                }
              } else {
                altgo = true;
                f1 = 1 + Math.round(_root.floorNum / 2 - 1) * 3;
              }
            }
          }
        }
      }
      if (_root.shopl == _root.lev) {
        f1 = 2;
      } else {
        if ((_root.bossRoom == _root.lev or _root.bossRoom2 == _root.lev) && _root.floorNum != 9) {
          f1 += 2;
        } else {
          if (_root.secretRoom == _root.lev) {
            f1 = 20;
          } else {
            if (_root.secretRoom2 == _root.lev) {
              f1 = [10, 26, 19, 23, 21];
              f1 = f1[_root.secretRoom2Type];
            } else {
              if (altgo && _root.altchap != 0 && _root.floorNum != 7 && _root.floorNum != 8) {
                f1 = 21 + Math.round(_root.floorNum / 2 - 1);
              }
            }
          }
        }
      }
      f2 = f1;
      if (_root.lev == 35 && !satan && _root.floorNum == 1) {
        f2 = 50;
      }
      if (_root.lev == _root.sacrificeRoom) {
        f1 = 24;
        f2 = 24;
      }
      if (_root.lev == _root.libraryRoom) {
        f1 = 25;
        f2 = 25;
      }
      if (_root.floorNum == 11) {
        f1 = 27;
        f2 = 27;
      }
      b.w1.gotoAndStop(f1);
      b.w2.gotoAndStop(f1);
      b.w3.gotoAndStop(f1);
      b.w4.gotoAndStop(f1);
      b.bg.gotoAndStop(f2);
      b.bg.d.gotoAndStop((_root.rax00 + _root.lev + _root.lev * _root.lev * (_root.rax20 + _root.lev) + (_root.rax10 + _root.lev) * _root.lev * _root.lev) % b.bg.d._totalframes + 1);
      b.w1.d.gotoAndStop((_root.rax01 + _root.lev + _root.lev * _root.lev * (_root.rax21 + _root.lev) + (_root.rax11 + _root.lev) * _root.lev * _root.lev) % b.w1.d._totalframes + 1);
      b.w2.d.gotoAndStop((_root.rax02 + _root.lev + _root.lev * _root.lev * (_root.rax22 + _root.lev) + (_root.rax12 + _root.lev) * _root.lev * _root.lev) % b.w2.d._totalframes + 1);
      b.w3.d.gotoAndStop((_root.rax03 + _root.lev + _root.lev * _root.lev * (_root.rax23 + _root.lev) + (_root.rax13 + _root.lev) * _root.lev * _root.lev) % b.w3.d._totalframes + 1);
      b.w4.d.gotoAndStop((_root.rax04 + _root.lev + _root.lev * _root.lev * (_root.rax24 + _root.lev) + (_root.rax14 + _root.lev) * _root.lev * _root.lev) % b.w4.d._totalframes + 1);
      xenf = Math.round((gridxs - gridx) / gridv + 1.5);
      yenf = Math.round((gridys - gridy) / gridv + 1.5);
      gxe = xenf;
      gye = yenf;
      xenf *= gridmax;
      var grid = new flash.display.BitmapData(xenf, yenf, false, 0);
      var grid2 = new flash.display.BitmapData(xenf, yenf, false, 0);
      var tests = new flash.display.BitmapData(300, 300, false, 0);
      _root.g.gotoAndPlay(60);
      timer = [];
      alltimer = [0, 0, 0, 0, 0, 0, 0, 0, 0];
      ballz = 0;
      ball = [];
      if (_root.floorNum >= 5) {
        mux = 1.25;
      } else {
        mux = 1;
      }
      v1 = 13;
      v2 = 60 + 15 * Math.min(10, _root.floorNum);
      v2 /= mux;
      p180 = 0.0174532925199433;
      p10 = 0.5235987755982988;
      v3 = 17;
      sizes = [5, 10, 8, v1, 16, 12, 0, v1, v1, 5, v1, v1, v1, v3, v3, v1, v1, v1, v3, 20, 40, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, 50, 0, v1, v1, v1, v1, v1, 35, v1, 35, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, 25, 25, 25, 25, 35, 27, 20, 0, 40, 25, v1, 40, 30, 20, v1, 35, v1, v1, 20, 20, 16, 55, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, v1, 20, 30, 35, 35, 40, 25];
      masses = [0, 5, 8 + _root.pickedUp[4] * 30, 0, 6, 3, 0, 6, 6, 8, 5, 3, 3, 3, 4, 10, 6, 6, 3, 50, 50, 7, 7, 7, 10, 7, 7, 15, 20, 10, 10, 10, 10, 1, 10, 10, 70, 1, 10, 10, 10, 10, 20, 50, 15, 70, 30, 30, 30, 30, 30, 30, 30, 10, 10, 10, 30, 30, 10, 10, 10, 7, 30, 30, 30, 30, 30, 30, 40, 20, 0, 40, 30, 20, 30, 20, 10, 3, 100, 20, 3, 50, 30, 30, 100, 5, 30, 30, 30, 30, 30, 30, 30, 30, 30, 30, 5, 30, 30, 80, 38, 80, 100];
      hps = [0, 10, 0, 0, 0, 0, 0, 0, 0, 10, 10, 10, 10, 3, 8, 15, 13, 13, 5, 22, 250, 15, 20, 20, 33, 20, 20, 15, 350, 10, 20, 10, 20, 0, 25, 25, 700, 0, 25, 25, 25, 20, 20, 550, 100, 530, v2, v2, v2 * 1.6, v2, v2, v2 * 0.5, v2, 20, 20, 25, 30, 40, 35, 20, 20, 10, 300, 240, 280, 400, 450, 110, 450, 350, 0, 60, 15, 8, 190, 75, 30, 12, 950, 140, 10, v2 * 3, v2 * 2, 100, 600, 10, 40, 40, 40, 40, 40, 40, 40, 40, 20, 40, 300, 200, 200, 250, 250, 300, 1000];
      hard = [1.570796326794897, 0.1570796326794897, p10 * 5, p10, p10, p10 * 2, 0, 0, 0, p10 * 5, p10, p10, p10, 0, 0, p10, p10, p10, 0, 0, p10, p10, p10, p10, p10, p10, 0, p10, p10, 0, p10, p10, p10, 0, 0, p10, p10, 0, p10, p10, p10, p10, 0, p10, p10, 0, p10, p10, p10, p10, p10, p10, p10, p10, p10, p10, p10, p10, p10, p10, p10, 0, p10, 0, 0, 0, 0, p10, p10, p10, 0, p10, p10, p10, p10, p10, p10, p10, 0, p10, 0, 0, 0, 0, 0, 0, p10, p10, p10, p10, p10, p10, p10, p10, p10, p10, 0, p10, p10, p10, p10, p10];
      hard[85] = p10;
      hard[54] = 0;
      hps[88] = 20;
      hps[62] *= 1.5;
      hps[43] *= 1.15;
      hps[65] *= 1.25;
      hps[57] *= 1.55;
      hps[45] *= 1.22;
      hps[36] *= 0.85;
      hps[89] = 20;
      hps[85] *= 0.65;
      hps[86] *= 0.9;
      hps[102] *= 2;
      if (_root.SecretUnlocked[45]) {
        hps[78] *= 1.25;
      }
      for (e in hops) {
        hps[e] *= mux;
      }
      wb = [];
      sizes[61] = v3;
      sizes[80] = v3;
      hardx = [];
      hardy = [];
      for (e in hard) {
        v1 = hard[e];
        siz = sizes[e];
        if (e == 14 or e == 13) {
          siz = 5;
        }
        if (v1 > 0) {
          hardx[e] = [];
          hardy[e] = [];
          a = 0;
          while (a < 6.283185307179586) {
            hardx[e][hardx[e].length] = Math.sin(a) * siz;
            hardy[e][hardy[e].length] = Math.cos(a) * siz;
            a += v1;
          }
        }
      }
      sizes[28] = 18;
      it1 = [true, true, true, true, true, true, true, true, true, true, true, true, true, true, true, true, true, true, true, true, true, true, true, true, true, true];
      watz = 0;
      flyer = 0;
      hearts = [];
      masks = [];
      if (_root.floorNum != 9 && (_root.challenge <= 0 or _root.challenge == 10)) {
        _root.heaven = _root.so.data.momKills >= 10;
      } else {
        _root.heaven = false;
      }
      parz = 0;
      par = [];
      createEmptyMovieClip('blorz', 297);
      lasth = 0;
      noBossDamage = true;
      org = new flash.display.BitmapData(40, 40, true, 13421772);
      v3 = 1;
      v2 = 20;
      v1.scale(v3, v3);
      v1.translate(v2, v2);
      org.draw(shaz, v1);
      f1 = 75;
      trg = createEmptyMovieClip('bggg', 290);
      bgg = new flash.display.BitmapData(gridxs, gridys - f1, true, 0);
      trg.attachBitmap(bgg, 1);
      trg._xscale = 100 / hdx;
      trg._yscale = trg._xscale;
      trg._y = f1;
      trg = createEmptyMovieClip('splala', 296);
      splat = new flash.display.BitmapData(gridxs, gridys, true, 0);
      trg.attachBitmap(splat, 1);
      trg._xscale = 100 / hdx;
      trg._yscale = trg._xscale;
      trg._alpha = 70;
      trg = createEmptyMovieClip('guta', 298);
      gut = new flash.display.BitmapData(gridxs, gridys, true, 0);
      trg.attachBitmap(gut, 1);
      trg._xscale = 100 / hdx;
      trg._yscale = trg._xscale;
      poi = new flash.geom.Point(0, 0);
      ref = [];
      mapd();
      sk = _root.sk;
      upa();
      webs = [];
      if (levz.length <= 1) {
        levz = new Array(200);
      }
      itemSpawnsPickups = [];
      itb = 0;
      lastcraf = -30;
      if (_root.playerx <= 0 or _root.newstartt) {
        _root.playerx = 320;
        _root.playery = 400;
      }
      player = create(_root.playerx, _root.playery, 0, 0, 0, 0, 1);
      if (_root.getup) {
        _root.getup = false;
        player.d.gotoAndStop(5);
      }
      if (_root.tell) {
        _root.tell = false;
        player.d.gotoAndStop(8);
      }
      player.mhp = _root.mhp;
      player.hp = _root.hp;
      if (_root.lev == _root.bossRoom && !beenHere) {
        if (haveTrinket(53)) {
          ++player.hp;
        }
      }
      Mouse.removeListener();
      if (mouseListener == undefined) {
        mouseListener = new Object();
        mouseListener.onMouseDown = function () {
          md = true;
        };

        mouseListener.onMouseUp = function () {
          md = false;
        };

      }
      Mouse.addListener(mouseListener);
      unpause = true;
      _root.pinfo = 2;
      fra = 0;
      player.fire = 0;
      player.fire1 = 0;
      ayenf = 0;
      axenf = 0;
      sob = 1;
      _root.st2._visible = false;
      _root.hud.st1._visible = _root.st2._visible;
      olfy = 0;
      olfx = 0;
      f1 = 440;
      switch (_root.door * 1) {
        case 0:
          olfx = -640;
          break;
        case 2:
          olfx = 640;
          break;
        case 1:
          olfy = f1;
          break;
        case 3:
          olfy = -f1;
      }
      _x = olfx;
      _y = olfy;
      shutdoor = 1;
      brr = [];
      brr2 = [];
      gibb = 0;
      if (_root.tex != undefined) {
        wtftex = _root.tex;
      }
      gameover = 0;
      justnow = 9;
      itemChargeRates = [0, 6, 3, 6, 1, 2, 1, 3, 0, 3, 3, 0, 2, 4, 0, 3, 2, 3, 3, 0, 0, 0, 0, 0, 0, 3, 2, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 6, 6, 0, 0, 0, 0, 6, 6, 6, 3, 0, 0, 0, 0, 0, 0, 6, 0, 0, 0, 4, 0, 0, 0, 0, 6, 0, 0, 3, 0, 6, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 4, 0, 0, 0, 0, 0, 4];
      itemChargeRates[96] = 3;
      itemChargeRates[106] = 6;
      itemChargeRates[105] = 1;
      itemChargeRates[107] = 1;
      itemChargeRates[118] = 6;
      itemChargeRates[131] = 2;
      itemChargeRates[126] = 6;
      itemChargeRates[120] = 4;
      itemChargeRates[135] = 2;
      itemChargeRates[141] = 6;
      itemChargeRates[152] = 2;
      wtfps2 = getTimer();
      wtfps = 35;
      wtfpsh = true;
      wtff = 60;
      _root.mapa._visible = true;
      _root.hud._visible = true;
      if (_root.shopl == _root.lev) {
        _root.shopa = true;
      }
      if (_root.libraryRoom == _root.lev) {
        _root.libraryUnlocked = true;
      }
      if (_root.boner == _root.lev) {
        _root.treasureRoomOpened = true;
      }
      if (_root.boner2 == _root.lev) {
        _root.treasureRoom2Opened = true;
      }
      secol = 0;
      minions = 0;
      flyby = 0;
      mom = [];
      worm = mom;
      mags = worm;
      mhelps = 0;
      if (random(2) == 0) {
      }
      ffly = 0;
      fiz = 0;
      nextbo = true;
      emosound = true;
      if (_root.lasth) {
        lasth = 50;
      }
      flyby2 = 0;
      flyby3 = 0;
      flyby4 = 0;
      playsave = -1;
      unic = -1;
      demon = -1;
      plo = 1;
      lastxy = 0;
      lastxx = 0;
      if (_root.chaf) {
        player.fire = -10;
        chaf = -20;
      }
      batteryTimer = _root.itemCharges;
      nocharge = 0;
      arenaRoom = 0;
      mhpp = 0;
      ahpp = 0;
      red = 0;
      blue = 0;
      shiz = [];
      if (_root.pickedUp[122] && player.hp < 1) {
        player._visible = false;
      }
    }
  }

  movieClip 6687  {
  }

  movieClip 6689  {
  }

  movieClip 6690  {
  }

  movieClip 6691  {

    frame 32 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 6693  {
  }

  movieClip 6694  {
  }

  movieClip 6695  {

    frame 32 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 6697  {
  }

  movieClip 6698  {
  }

  movieClip 6699  {

    frame 32 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 6701  {
  }

  movieClip 6702  {
  }

  movieClip 6703  {

    frame 32 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 6705  {
  }

  movieClip 6706  {
  }

  movieClip 6707  {

    frame 32 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 6709  {
  }

  movieClip 6710  {

    frame 32 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 6712  {
  }

  movieClip 6713  {
  }

  movieClip 6714  {

    frame 32 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 6716  {
  }

  movieClip 6717  {
  }

  movieClip 6718  {

    frame 32 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 6720  {
  }

  movieClip 6721  {
  }

  movieClip 6722  {

    frame 32 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 6724  {
  }

  movieClip 6725  {
  }

  movieClip 6726  {

    frame 32 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 6737  {
  }

  movieClip 6738  {

    frame 34 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 6740  {
  }

  movieClip 6741  {
  }

  movieClip 6742  {

    frame 32 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 6744  {
  }

  movieClip 6745  {
  }

  movieClip 6746  {

    frame 32 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 6748  {
  }

  movieClip 6750  {
  }

  movieClip 6751  {

    frame 32 {
      _parent.gotoAndStop(1);
    }
  }

  movieClip 6752  {

    frame 1 {
      stop();
    }
  }

  movieClip 6754  {

    frame 124 {
      stop();
      _visible = false;
    }
  }

  frame 3 {
    _root.goblack();
  }

  movieClip 6760  {

    frame 1 {
      f1 = Math.round(_root.floorNum / 2);
      _root.tex = f1;
      gotoAndStop(f1);
    }
  }

  movieClip 6762  {
  }

  movieClip 6764  {
  }

  movieClip 6766  {
  }

  movieClip 6769  {
  }

  movieClip 6772  {
  }

  movieClip 6773  {

    frame 1 {
      gotoAndStop(_root.characterID + 1);
    }
  }

  movieClip 6775  {
  }

  movieClip 6778  {
  }

  movieClip 6787  {
  }

  movieClip 6790  {
  }

  movieClip 6792  {
  }

  movieClip 6794  {
  }

  movieClip 6798  {
  }

  movieClip 6800  {
  }

  movieClip 6801  {
  }

  movieClip 6803  {
  }

  movieClip 6804  {
  }

  movieClip 6806  {
  }

  movieClip 6808  {
  }

  movieClip 6810  {
  }

  movieClip 6812  {
  }

  movieClip 6814  {
  }

  movieClip 6816  {
  }

  movieClip 6818  {
  }

  movieClip 6819  {
  }

  movieClip 6821  {
  }

  movieClip 6823  {
  }

  movieClip 6825  {
  }

  movieClip 6827  {
  }

  movieClip 6828  {
  }

  movieClip 6832  {
  }

  movieClip 6838  {
  }

  movieClip 6839  {
  }

  movieClip 6850  {
  }

  movieClip 6853  {
  }

  movieClip 6855  {
  }

  movieClip 6860  {
  }

  movieClip 6868  {
  }

  movieClip 6870  {
  }

  movieClip 6911  {
  }

  movieClip 6921  {
  }

  movieClip 6948  {
  }

  movieClip 6953  {
  }

  movieClip 6960  {
  }

  movieClip 6961  {
  }

  movieClip 6982  {
  }

  movieClip 6983  {

    frame 1 {
      gotoAndStop(random(_totalframes) + 1);
    }
  }

  movieClip 6984  {

    frame 1 {
      _root.soundy('levelbumper.mp3', 100);
    }

    frame 2 {
      if (_root.SecretUnlocked[4]) {
        f1.gotoAndStop(2);
      } else {
        f1.gotoAndStop(1);
      }
      f2.gotoAndStop(_root.floorNum);
      f1.d.gotoAndStop(_root.floorNum);
    }

    frame 224 {
      _root.gotoAndStop('game');
    }
  }

  frame 4 {
    goblack();
    _root.olda._visible = false;
    _root.door = undefined;
  }

  movieClip 6986  {

    frame 1 {
      gotoAndStop(random(_totalframes) + 1);
    }
  }

  movieClip 6988  {

    frame 1 {
      gotoAndStop(_root.characterID + 1);
    }
  }

  movieClip 6990  {
  }

  movieClip 6991  {

    frame 20 {
      _root.soundy('bossintro.mp3', 100);
    }

    frame 158 {
      _root.gotoAndStop('game');
    }
  }

  frame 5 {
    _root.goblack();
  }

  frame 5 {
    _root.newstartt = true;
  }

  movieClip 6995  {
  }

  movieClip 6997  {
  }

  movieClip 6998  {
  }

  movieClip 6999  {
  }

  button 7004 {

    on (release, keyPress '<Space>') {
      if (pos == 4) {
      } else {
        if (pos == 1) {
          achsh();
        } else {
          if (_parent.ex._currentframe == 2) {
            _root.nooo();
          } else {
            if (xp > 0) {
              pos = undefined;
            } else {
              if (xp == 0) {
                pos = 3;
              } else {
                if (_root.characterID == 0 or _root.SecretUnlocked[_root.characterID] && _root.characterID < 5 or _root.characterID == 5 && _root.SecretUnlocked[54] or _root.characterID == 6 && _root.SecretUnlocked[88]) {
                  _root.challenge = undefined;
                  _root.darky(150);
                }
              }
            }
          }
        }
      }
    }
  }

  button 7008 {

    on (release) {
      pos = 2;
    }
  }

  button 7011 {

    on (release) {
      pos = 1;
    }
  }

  button 7012 {

    on (release) {
      pos = 5;
    }
  }

  button 7016 {

    on (release) {
      _root.soundy('character_select_right.wav');
      gotoAndStop(3);
    }
  }

  button 7017 {

    on (release) {
      _root.soundy('character_select_right.wav');
      gotoAndStop(1);
    }
  }

  movieClip 7018  {

    frame 1 {
      stop();
      _parent.keepItem();
    }

    frame 3 {
      _parent.keepItem();
    }
  }

  movieClip 7024  {
  }

  movieClip 7027  {
  }

  movieClip 7030  {
  }

  movieClip 7032  {
  }

  button 7033 {

    on (release) {
      if (_parent.pos == 3) {
        --characterID;
        _root.soundy('character_select_left.wav');
      }
    }
  }

  button 7034 {

    on (release) {
      if (_parent.pos == 3) {
        ++characterID;
        _root.soundy('character_select_right.wav');
      }
    }
  }

  movieClip 7037  {
  }

  movieClip 7039  {
  }

  movieClip 7041  {

    frame 1 {
      if (_root.SecretUnlocked[38]) {
        gotoAndStop(2);
      } else {
        gotoAndStop(1);
      }
    }
  }

  movieClip 7044  {
  }

  movieClip 7047  {
  }

  movieClip 7050  {
  }

  movieClip 7053  {
  }

  movieClip 7055  {
  }

  movieClip 7058  {
  }

  movieClip 7059  {

    frame 1 {
      stop();
    }
  }

  movieClip 7061  {
  }

  movieClip 7064  {
  }

  movieClip 7067  {
  }

  button 7071 {

    on (release) {
      rander();
    }
  }

  movieClip 7072  {

    frame 1 {
      function rander() {
        if (!done) {
          done = true;
          f2 = characterID;
          if (rand.length > 1) {
            f1 = rand[random(rand.length)];
            characterID = f1;
            _parent.pos = 3;
            _root.challenge = undefined;
            _root.darky(150);
            _root.tex = rand + ' ' + characterID;
          }
        }
      }

      function onEnterFrame() {
        if (Key.isDown(82)) {
          if (nor) {
            rander();
            nor = false;
          }
        } else {
          nor = true;
        }
        if (!_root.SecretUnlocked[41]) {
          chars = 6;
        } else {
          chars = 7;
        }
        if (chars == 6) {
          while (characterID > 5) {
            characterID -= 6;
          }
          while (characterID < 0) {
            characterID += 6;
          }
        } else {
          while (characterID > 6) {
            characterID -= 7;
          }
          while (characterID < 0) {
            characterID += 7;
          }
        }
        f2 = 360 / chars;
        _root.characterID = characterID;
        if (characterID == 5) {
          if (chars == 6) {
            _root.characterID = 6;
          } else {
            _root.characterID = 4;
          }
        } else {
          if (characterID == 4) {
            _root.characterID = 5;
          }
        }
        xenf = rp + rbew * 3 - characterID * f2;
        while (xenf >= 180) {
          xenf -= 360;
        }
        while (xenf >= 180) {
          xenf -= 360;
        }
        while (rp < 180) {
          rp += 360;
        }
        rbew -= xenf * 0.1;
        rbew *= 0.8;
        rp += rbew;
        inc.gotoAndStop(characterID + 1);
        f1 = _root.SecretUnlocked[characterID] && characterID != 4 or characterID == 4 && _root.SecretUnlocked[54];
        if (_root.characterID == 6) {
          inc.gotoAndStop(7);
          f1 = _root.SecretUnlocked[88];
        }
        if (f1) {
          inc.d.gotoAndStop(1);
        } else {
          inc.d.gotoAndStop(2);
        }
        rand = [0];
        e = 0;
        while (e < chars) {
          trg = this['i' + e];
          if (e == 5) {
            if (chars == 6) {
              trg = i6;
            } else {
              trg = i4;
            }
          } else {
            if (e == 4) {
              trg = i5;
            }
          }
          if (chars == 6) {
            f1 = [0, 3, 2, 1, 4, 5];
            o = -f1[e];
          } else {
            o = e;
            f1 = [0, 3, 2, 1, 4, 5, 6];
            o = -f1[e];
          }
          f1 = ((rp + o * f2) / 180) * Math.PI;
          trg._x = -Math.sin(f1) * 100 + 100;
          f1 = Math.cos(f1) * 25 + 65;
          trg._y = f1;
          trg._yscale = f1;
          trg._xscale = trg._yscale;
          trg._alpha = trg._yscale;
          trg._alpha += 20;
          trg.swapDepths(Math.round(trg._y) * 10 + e);
          if (chars == 6) {
            f1 = [0, 3, 2, 1, 54, 88];
          } else {
            f1 = [0, 3, 2, 1, 54, 41, 88];
          }
          if (_root.SecretUnlocked[f1[e]]) {
            trg.gotoAndStop(1);
            rand.push(-o);
          } else {
            trg.gotoAndStop(2);
          }
          ++e;
        }
      }

      rp = 360;
      characterID = 0;
      rbew = 0;
    }
  }

  button 7076 {

    on (release) {
      if (pos == 3) {
        if (_root.characterID == 0 or _root.SecretUnlocked[_root.characterID] && _root.characterID < 5 or _root.characterID == 5 && _root.SecretUnlocked[54] or _root.characterID == 6 && _root.SecretUnlocked[88]) {
          _root.challenge = undefined;
          _root.darky(150);
        }
      }
    }
  }

  button 7079 {

    on (release) {
      if (pos == 0) {
        _root.creskip = true;
        if (_root.so.data.momKills > 0) {
          _root.gotoAndStop(21);
        } else {
          _root.gotoAndStop(20);
        }
      } else {
        pos = 0;
      }
    }
  }

  button 7080 {

    on (release) {
      pos = undefined;
    }
  }

  movieClip 7085  {
  }

  movieClip 7086  {
  }

  button 7092 {

    on (release) {
      _root.gotoAndStop(22);
    }
  }

  movieClip 7093  {
  }

  button 7098 {

    on (release) {
      _root.gotoAndStop(23);
    }
  }

  movieClip 7099  {
  }

  button 7104 {

    on (release) {
      _root.gotoAndStop(24);
    }
  }

  movieClip 7105  {
  }

  button 7109 {

    on (release) {
      _root.gotoAndStop(9);
    }
  }

  button 7113 {

    on (release) {
      _root.gotoAndStop(10);
    }
  }

  button 7117 {

    on (release) {
      _root.gotoAndStop(11);
    }
  }

  button 7121 {

    on (release) {
      _root.gotoAndStop(12);
    }
  }

  button 7125 {

    on (release) {
      _root.gotoAndStop(13);
    }
  }

  button 7129 {

    on (release) {
      _root.gotoAndStop(14);
    }
  }

  button 7133 {

    on (release) {
      _root.gotoAndStop(15);
    }
  }

  button 7137 {

    on (release) {
      _root.gotoAndStop(16);
    }
  }

  button 7141 {

    on (release) {
      _root.gotoAndStop(17);
    }
  }

  button 7145 {

    on (release) {
      _root.gotoAndStop(18);
    }
  }

  button 7149 {

    on (release) {
      _root.gotoAndStop(19);
    }
  }

  movieClip 7150  {

    frame 1 {
      stop();
    }
  }

  movieClip 7162  {
  }

  movieClip 7163  {
  }

  movieClip 7164  {
  }

  movieClip 7165  {
  }

  movieClip 7166  {
  }

  button 7170 {

    on (release) {
      if (_root.linx) {
        _parent.ex.gotoAndStop(3);
      } else {
        _parent.ex.nextFrame();
      }
    }
  }

  button 7174 {

    on (release) {
      nextFrame();
    }
  }

  movieClip 7175  {

    frame 1 {
      stop();
    }
  }

  button 7179 {

    on (release) {
      achsh();
    }
  }

  button 7183 {

    on (release) {
      pos = 7;
