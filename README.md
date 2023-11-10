# Calendario2024html
Codigo para calendario con notas, espero les ayude todo el codigo, el problema es que la idea era hacerlo para que uno pudoiera agregar sus notas y que se mantubieran en los cookies

<!DOCTYPE html>
<html>
<head>
<meta http-equiv="cache-control" content="no-cache"><meta http-equiv="Pragma" content="no-cache"><meta http-equiv="Expires" content="-1"><style type="text/css"></style>


<meta charset="UTF-8">
    <title>Calendario 2024</title>
<style>
        table {
            border-collapse: collapse;
            width: 100%;
            border: 1px solid #e3e3ed;
        }

    th, td {
            text-align: center;
            padding: 8px;
            border: 1px solid black;
        }

        th {
            color: white;
        }

        .mes{
          background-color: #45a049;
        }

        .nomes {
            background:#888;
        }

        td {
            background-color: #e3e3ed;
          padding:0px;
        }

        textarea {
          background-color: #45a0d9;
          height: 100px;
          width: 100%;
          border-radius:5px;
          padding: 2px;
        border: 1px solid #e3e3ed;

}
        body {
            text-align:center;
        }
        .Calendario {
            font-size: 60px;
            font-style: bold;
        }
        seccion {
          position: fixed; /* Posición fija para que se mantenga en su lugar al desplazarse la página */
          right: 0px; /* Ubica el elemento a la mitad del ancho de la ventana */
          top: 0px; /* Ubica el elemento a la mitad de la altura de la ventana */
          z-index: 9999; /* Define la profundidad del elemento flotante */
          padding:10px;
          height:35px;
          background:#1118;
          width:110px;
          text-align:center;
          border-radius:0px 0px 0px 20px;
          align-items: center;
          align-content:center;
        }  
        button {
            background:#4ef;
            border-radius:50px;
            padding:5px
        }
</style>
</head>
<body>
    <p class="Calendario">Calendario 2024</p>
    <h1>Enero</h1>
    <table>
        <tbody><tr>
            <th class="mes">1</th>
            <th class="mes">2</th>
            <th class="mes">3</th>
            <th class="mes">4</th>
            <th class="mes">5</th>
            <th class="mes">6</th>
            <th class="mes">7</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-1-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-2-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-3-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-4-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-5-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-6-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-7-1" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">8</th>
            <th class="mes">9</th>
            <th class="mes">10</th>
            <th class="mes">11</th>
            <th class="mes">12</th>
            <th class="mes">13</th>
            <th class="mes">14</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-8-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-9-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-10-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-11-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-12-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-13-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-14-1" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">15</th>
            <th class="mes">16</th>
            <th class="mes">17</th>
            <th class="mes">18</th>
            <th class="mes">19</th>
            <th class="mes">20</th>
            <th class="mes">21</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-15-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-16-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-17-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-18-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-19-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-20-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-21-1" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">22</th>
            <th class="mes">23</th>
            <th class="mes">24</th>
            <th class="mes">25</th>
            <th class="mes">26</th>
            <th class="mes">27</th>
            <th class="mes">28</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-22-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-23-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-24-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-25-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-26-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-27-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-28-1" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">29</th>
            <th class="mes">30</th>
            <th class="mes">31</th>
            <th class="nomes">1</th>
            <th class="nomes">2</th>
            <th class="nomes">3</th>
            <th class="nomes">4</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-29-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-30-1" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-31-1" placeholder="Notas"></textarea></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </tbody></table>
    <h1>Febrero</h1>
    <table>
        <tbody><tr>
            <th class="nomes">29</th>
            <th class="nomes">30</th>
            <th class="nomes">31</th>
            <th class="mes">1</th>
            <th class="mes">2</th>
            <th class="mes">3</th>
            <th class="mes">4</th>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td><textarea type="text" id="nota-1-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-2-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-3-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-4-2" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">5</th>
            <th class="mes">6</th>
            <th class="mes">7</th>
            <th class="mes">8</th>
            <th class="mes">9</th>
            <th class="mes">10</th>
            <th class="mes">11</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-5-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-6-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-7-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-8-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-9-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-10-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-11-2" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">12</th>
            <th class="mes">13</th>
            <th class="mes">14</th>
            <th class="mes">15</th>
            <th class="mes">16</th>
            <th class="mes">17</th>
            <th class="mes">18</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-12-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-13-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-14-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-15-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-16-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-17-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-18-2" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">19</th>
            <th class="mes">20</th>
            <th class="mes">21</th>
            <th class="mes">22</th>
            <th class="mes">23</th>
            <th class="mes">24</th>
            <th class="mes">25</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-19-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-20-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-21-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-22-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-23-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-24-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-25-2" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">26</th>
            <th class="mes">27</th>
            <th class="mes">28</th>
            <th class="mes">29</th>
            <th class="nomes">1</th>
            <th class="nomes">2</th>
            <th class="nomes">3</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-26-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-27-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-28-2" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-29-2" placeholder="Notas"></textarea></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </tbody></table>
    <h1>Marzo</h1>
    <table>
        <tbody><tr>
            <th class="nomes">26</th>
            <th class="nomes">27</th>
            <th class="nomes">28</th>
            <th class="nomes">29</th>
            <th class="mes">1</th>
            <th class="mes">2</th>
            <th class="mes">3</th>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td><textarea type="text" id="nota-1-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-2-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-3-3" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">4</th>
            <th class="mes">5</th>
            <th class="mes">6</th>
            <th class="mes">7</th>
            <th class="mes">8</th>
            <th class="mes">9</th>
            <th class="mes">10</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-4-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-5-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-6-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-7-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-8-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-9-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-10-3" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">11</th>
            <th class="mes">12</th>
            <th class="mes">13</th>
            <th class="mes">14</th>
            <th class="mes">15</th>
            <th class="mes">16</th>
            <th class="mes">17</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-11-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-12-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-13-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-14-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-15-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-16-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-17-3" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">18</th>
            <th class="mes">19</th>
            <th class="mes">20</th>
            <th class="mes">21</th>
            <th class="mes">22</th>
            <th class="mes">23</th>
            <th class="mes">24</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-18-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-19-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-20-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-21-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-22-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-23-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-24-3" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">25</th>
            <th class="mes">26</th>
            <th class="mes">27</th>
            <th class="mes">28</th>
            <th class="mes">29</th>
            <th class="mes">30</th>
            <th class="mes">31</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-25-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-26-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-27-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-28-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-29-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-30-3" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-31-3" placeholder="Notas"></textarea></td>
        </tr>
    </tbody></table>
        <h1>Abril</h1>
    <table>
        <tbody><tr>
            <th class="mes">1</th>
            <th class="mes">2</th>
            <th class="mes">3</th>
            <th class="mes">4</th>
            <th class="mes">5</th>
            <th class="mes">6</th>
            <th class="mes">7</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-1-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-2-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-3-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-4-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-5-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-6-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-7-4" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">8</th>
            <th class="mes">9</th>
            <th class="mes">10</th>
            <th class="mes">11</th>
            <th class="mes">12</th>
            <th class="mes">13</th>
            <th class="mes">14</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-8-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-9-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-10-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-11-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-12-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-13-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-14-4" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">15</th>
            <th class="mes">16</th>
            <th class="mes">17</th>
            <th class="mes">18</th>
            <th class="mes">19</th>
            <th class="mes">20</th>
            <th class="mes">21</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-15-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-16-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-17-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-18-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-19-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-20-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-21-4" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">22</th>
            <th class="mes">23</th>
            <th class="mes">24</th>
            <th class="mes">25</th>
            <th class="mes">26</th>
            <th class="mes">27</th>
            <th class="mes">28</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-22-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-23-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-24-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-25-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-26-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-27-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-28-4" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">29</th>
            <th class="mes">30</th>
            <th class="nomes">1</th>
            <th class="nomes">2</th>
            <th class="nomes">3</th>
            <th class="nomes">4</th>
            <th class="nomes">5</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-29-4" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-30-4" placeholder="Notas"></textarea></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </tbody></table>
        <h1>Mayo</h1>
    <table>
        <tbody><tr>
            <th class="nomes">29</th>
            <th class="nomes">30</th>
            <th class="mes">1</th>
            <th class="mes">2</th>
            <th class="mes">3</th>
            <th class="mes">4</th>
            <th class="mes">5</th>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td><textarea type="text" id="nota-1-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-2-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-3-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-4-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-5-5" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">6</th>
            <th class="mes">7</th>
            <th class="mes">8</th>
            <th class="mes">9</th>
            <th class="mes">10</th>
            <th class="mes">11</th>
            <th class="mes">12</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-6-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-7-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-8-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-9-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-10-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-11-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-12-5" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">13</th>
            <th class="mes">14</th>
            <th class="mes">15</th>
            <th class="mes">16</th>
            <th class="mes">17</th>
            <th class="mes">18</th>
            <th class="mes">19</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-13-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-14-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-15-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-16-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-17-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-18-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-19-5" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">20</th>
            <th class="mes">21</th>
            <th class="mes">22</th>
            <th class="mes">23</th>
            <th class="mes">24</th>
            <th class="mes">25</th>
            <th class="mes">26</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-20-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-21-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-22-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-23-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-24-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-25-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-26-5" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">27</th>
            <th class="mes">28</th>
            <th class="mes">29</th>
            <th class="mes">30</th>
            <th class="mes">31</th>
            <th class="nomes">1</th>
            <th class="nomes">2</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-27-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-28-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-29-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-30-5" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-31-5" placeholder="Notas"></textarea></td>
            <td></td>
            <td></td>
        </tr>
    </tbody></table>
        <h1>Junio</h1>
    <table>
        <tbody><tr>
            <th class="nomes">27</th>
            <th class="nomes">28</th>
            <th class="nomes">29</th>
            <th class="nomes">30</th>
            <th class="nomes">31</th>
            <th class="mes">1</th>
            <th class="mes">2</th>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td><textarea type="text" id="nota-1-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-2-6" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">3</th>
            <th class="mes">4</th>
            <th class="mes">5</th>
            <th class="mes">6</th>
            <th class="mes">7</th>
            <th class="mes">8</th>
            <th class="mes">9</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-3-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-4-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-5-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-6-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-7-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-8-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-9-6" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">10</th>
            <th class="mes">11</th>
            <th class="mes">12</th>
            <th class="mes">13</th>
            <th class="mes">14</th>
            <th class="mes">15</th>
            <th class="mes">16</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-10-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-11-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-12-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-13-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-14-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-15-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-16-6" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">17</th>
            <th class="mes">18</th>
            <th class="mes">19</th>
            <th class="mes">20</th>
            <th class="mes">21</th>
            <th class="mes">22</th>
            <th class="mes">23</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-17-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-18-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-19-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-20-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-21-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-22-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-23-6" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">24</th>
            <th class="mes">25</th>
            <th class="mes">26</th>
            <th class="mes">27</th>
            <th class="mes">28</th>
            <th class="mes">29</th>
            <th class="mes">30</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-24-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-25-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-26-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-27-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-28-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-29-6" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-30-6" placeholder="Notas"></textarea></td>
        </tr>
    </tbody></table>
        <h1>Julio</h1>
    <table>
        <tbody><tr>
            <th class="mes">1</th>
            <th class="mes">2</th>
            <th class="mes">3</th>
            <th class="mes">4</th>
            <th class="mes">5</th>
            <th class="mes">6</th>
            <th class="mes">7</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-1-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-2-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-3-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-4-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-5-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-6-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-7-7" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">8</th>
            <th class="mes">9</th>
            <th class="mes">10</th>
            <th class="mes">11</th>
            <th class="mes">12</th>
            <th class="mes">13</th>
            <th class="mes">14</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-8-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-9-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-10-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-11-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-12-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-13-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-14-7" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">15</th>
            <th class="mes">16</th>
            <th class="mes">17</th>
            <th class="mes">18</th>
            <th class="mes">19</th>
            <th class="mes">20</th>
            <th class="mes">21</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-15-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-16-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-17-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-18-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-19-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-20-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-21-7" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">22</th>
            <th class="mes">23</th>
            <th class="mes">24</th>
            <th class="mes">25</th>
            <th class="mes">26</th>
            <th class="mes">27</th>
            <th class="mes">28</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-22-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-23-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-24-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-25-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-26-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-27-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-28-7" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">29</th>
            <th class="mes">30</th>
            <th class="mes">31</th>
            <th class="nomes">1</th>
            <th class="nomes">2</th>
            <th class="nomes">3</th>
            <th class="nomes">4</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-29-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-30-7" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-31-7" placeholder="Notas"></textarea></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </tbody></table>

<h1>Agosto</h1>
<table>
<tbody><tr class="dias"> <td>Lunes</td><td>Martes</td><td>Miercoles</td><td>Jueves</td><td>Viernes</td><td>Sábado</td><td>Domingo</td></tr>
        <tr>
            <th class="nomes">29</th>
            <th class="nomes">30</th>
            <th class="nomes">31</th>
            <th class="mes">1</th>
            <th class="mes">2</th>
            <th class="mes">3</th>
            <th class="mes">4</th>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td><textarea type="text" id="nota-1-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-2-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-3-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-4-8" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">5</th>
            <th class="mes">6</th>
            <th class="mes">7</th>
            <th class="mes">8</th>
            <th class="mes">9</th>
            <th class="mes">10</th>
            <th class="mes">11</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-5-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-6-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-7-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-8-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-9-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-10-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-11-8" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">12</th>
            <th class="mes">13</th>
            <th class="mes">14</th>
            <th class="mes">15</th>
            <th class="mes">16</th>
            <th class="mes">17</th>
            <th class="mes">18</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-12-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-13-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-14-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-15-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-16-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-17-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-18-8" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">19</th>
            <th class="mes">20</th>
            <th class="mes">21</th>
            <th class="mes">22</th>
            <th class="mes">23</th>
            <th class="mes">24</th>
            <th class="mes">25</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-19-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-20-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-21-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-22-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-23-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-24-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-25-8" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">26</th>
            <th class="mes">27</th>
            <th class="mes">28</th>
            <th class="mes">29</th>
            <th class="mes">30</th>
            <th class="mes">31</th>
            <th class="nomes">1</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-26-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-27-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-28-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-29-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-30-8" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-31-8" placeholder="Notas"></textarea></td>
            <td></td>
        </tr>
    </tbody></table>

        <h1>Septiembre</h1>

<table>
        <tbody><tr>
            <th class="nomes">26</th>
            <th class="nomes">27</th>
            <th class="nomes">28</th>
            <th class="nomes">29</th>
            <th class="nomes">30</th>
            <th class="nomes">31</th>
            <th class="mes">1</th>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td><textarea type="text" id="nota-1-9" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">2</th>
            <th class="mes">3</th>
            <th class="mes">4</th>
            <th class="mes">5</th>
            <th class="mes">6</th>
            <th class="mes">7</th>
            <th class="mes">8</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-2-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-3-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-4-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-5-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-6-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-7-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-8-9" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">9</th>
            <th class="mes">10</th>
            <th class="mes">11</th>
            <th class="mes">12</th>
            <th class="mes">13</th>
            <th class="mes">14</th>
            <th class="mes">15</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-9-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-10-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-11-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-12-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-13-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-14-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-15-9" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">16</th>
            <th class="mes">17</th>
            <th class="mes">18</th>
            <th class="mes">19</th>
            <th class="mes">20</th>
            <th class="mes">21</th>
            <th class="mes">22</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-16-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-17-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-18-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-19-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-20-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-21-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-22-9" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">23</th>
            <th class="mes">24</th>
            <th class="mes">25</th>
            <th class="mes">26</th>
            <th class="mes">27</th>
            <th class="mes">28</th>
            <th class="mes">29</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-23-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-24-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-25-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-26-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-27-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-28-9" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-29-9" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">30</th>
            <th class="nomes">1</th>
            <th class="nomes">2</th>
            <th class="nomes">3</th>
            <th class="nomes">4</th>
            <th class="nomes">5</th>
            <th class="nomes">6</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-30-9" placeholder="Notas"></textarea></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </tbody></table>

<h1>Octubre</h1>
<table>
        <tbody><tr>
            <th class="nomes">30</th>
            <th class="mes">1</th>
            <th class="mes">2</th>
            <th class="mes">3</th>
            <th class="mes">4</th>
            <th class="mes">5</th>
            <th class="mes">6</th>
        </tr>
        <tr>
            <td></td>
            <td><textarea type="text" id="nota-1-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-2-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-3-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-4-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-5-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-6-10" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">7</th>
            <th class="mes">8</th>
            <th class="mes">9</th>
            <th class="mes">10</th>
            <th class="mes">11</th>
            <th class="mes">12</th>
            <th class="mes">13</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-7-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-8-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-9-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-10-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-11-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-12-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-13-10" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">14</th>
            <th class="mes">15</th>
            <th class="mes">16</th>
            <th class="mes">17</th>
            <th class="mes">18</th>
            <th class="mes">19</th>
            <th class="mes">20</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-14-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-15-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-16-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-17-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-18-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-19-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-20-10" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">21</th>
            <th class="mes">22</th>
            <th class="mes">23</th>
            <th class="mes">24</th>
            <th class="mes">25</th>
            <th class="mes">26</th>
            <th class="mes">27</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-21-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-22-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-23-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-24-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-25-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-26-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-27-10" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">28</th>
            <th class="mes">29</th>
            <th class="mes">30</th>
            <th class="mes">31</th>
            <th class="nomes">1</th>
            <th class="nomes">2</th>
            <th class="nomes">3</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-28-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-29-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-30-10" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-31-10" placeholder="Notas"></textarea></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>

</tbody></table>

<h1>Noviembre</h1>
<table>
        <tbody><tr>
            <th class="nomes">28</th>
            <th class="nomes">29</th>
            <th class="nomes">30</th>
            <th class="nomes">31</th>
            <th class="mes">1</th>
            <th class="mes">2</th>
            <th class="mes">3</th>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td><textarea type="text" id="nota-1-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-2-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-3-11" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">4</th>
            <th class="mes">5</th>
            <th class="mes">6</th>
            <th class="mes">7</th>
            <th class="mes">8</th>
            <th class="mes">9</th>
            <th class="mes">10</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-4-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-5-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-6-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-7-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-8-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-9-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-10-11" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">11</th>
            <th class="mes">12</th>
            <th class="mes">13</th>
            <th class="mes">14</th>
            <th class="mes">15</th>
            <th class="mes">16</th>
            <th class="mes">17</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-11-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-12-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-13-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-14-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-15-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-16-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-17-11" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">18</th>
            <th class="mes">19</th>
            <th class="mes">20</th>
            <th class="mes">21</th>
            <th class="mes">22</th>
            <th class="mes">23</th>
            <th class="mes">24</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-18-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-19-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-20-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-21-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-22-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-23-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-24-11" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">25</th>
            <th class="mes">26</th>
            <th class="mes">27</th>
            <th class="mes">28</th>
            <th class="mes">29</th>
            <th class="mes">30</th>
            <th class="nomes">1</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-25-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-26-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-27-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-28-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-29-11" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-30-11" placeholder="Notas"></textarea></td>
            <td></td>
        </tr>
</tbody></table>

<h1>Diciembre</h1>
<table>
        <tbody>
          <tr>
            <th class="nomes">25</th>
            <th class="nomes">26</th>
            <th class="nomes">27</th>
            <th class="nomes">28</th>
            <th class="nomes">29</th>
            <th class="nomes">30</th>
            <th class="mes">1</th>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td><textarea type="text" id="nota-1-12" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">2</th>
            <th class="mes">3</th>
            <th class="mes">4</th>
            <th class="mes">5</th>
            <th class="mes">6</th>
            <th class="mes">7</th>
            <th class="mes">8</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-2-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-3-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-4-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-5-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-6-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-7-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-8-12" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">9</th>
            <th class="mes">10</th>
            <th class="mes">11</th>
            <th class="mes">12</th>
            <th class="mes">13</th>
            <th class="mes">14</th>
            <th class="mes">15</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-9-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-10-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-11-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-12-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-13-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-14-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-15-12" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">16</th>
            <th class="mes">17</th>
            <th class="mes">18</th>
            <th class="mes">19</th>
            <th class="mes">20</th>
            <th class="mes">21</th>
            <th class="mes">22</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-16-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-17-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-18-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-19-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-20-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-21-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-22-12" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">23</th>
            <th class="mes">24</th>
            <th class="mes">25</th>
            <th class="mes">26</th>
            <th class="mes">27</th>
            <th class="mes">28</th>
            <th class="mes">29</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-23-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-24-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-25-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-26-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-27-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-28-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-29-12" placeholder="Notas"></textarea></td>
        </tr>
        <tr>
            <th class="mes">30</th>
            <th class="mes">31</th>
            <th class="nomes">1</th>
            <th class="nomes">2</th>
            <th class="nomes">3</th>
            <th class="nomes">4</th>
            <th class="nomes">5</th>
        </tr>
        <tr>
            <td><textarea type="text" id="nota-30-12" placeholder="Notas"></textarea></td>
            <td><textarea type="text" id="nota-31-12" placeholder="Notas"></textarea></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </tbody></table>
    <seccion><button onclick="saveInputs()" alt="Debes de guardar para que se mantengan los datos">Guardar</button></seccion>

<script>
        // Función para guardar los valores de los campos en cookies
        function saveInputs() {
            var inputs = document.getElementsByTagName('textarea');
            for (var i = 0; i < inputs.length; i++) {
                var input = inputs[i];
                document.cookie = input.id + '=' + input.value;
            }
        }

        // Función para cargar los valores de los campos desde cookies
        function loadInputs() {
            var inputs = document.getElementsByTagName('textarea');
            for (var i = 0; i < inputs.length; i++) {
                var input = inputs[i];
                var cookieValue = getCookie(input.id);
                if (cookieValue) {
                    input.value = cookieValue;
                }
            }
        }

        // Función para obtener el valor de una cookie por nombre
        function getCookie(name) {
            var value = '; ' + document.cookie;
            var parts = value.split('; ' + name + '=');
            if (parts.length == 2) return parts.pop().split(';').shift();
        }

        // Llamar a la función de carga al cargar la página
        loadInputs();
</script>
    
<script>
function getCookieValue(cookieName) {
  var xhr = new XMLHttpRequest();
  xhr.open('GET', '/getCookie?cookieName=' + cookieName, true);
  xhr.onload = function() {
    if (xhr.status === 200) {
      var cookieValue = JSON.parse(xhr.responseText).cookieValue;
      console.log(cookieValue);
    } else {
      console.error('Error getting cookie value: ' + xhr.statusText);
    }
  };
  xhr.send();
}

function setCookieValue(cookieName, cookieValue) {
  var xhr = new XMLHttpRequest();
  xhr.open('POST', '/setCookie', true);
  xhr.setRequestHeader('Content-Type', 'application/json');
  xhr.send(JSON.stringify({ cookieName: cookieName, cookieValue: cookieValue }));
}
</script>
</body>
</html>
