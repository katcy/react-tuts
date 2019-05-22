import React from "react";
import ReactDOM from "react-dom";

import {Map as LeafletMap,TileLayer,Marker,Popup} from 'react-leaflet';
import 'leaflet/dist/leaflet.css';

import L from 'leaflet'

import "./styles.css";

let newIcon = new L.icon({
  iconUrl:'https://escondidolegion.org/wp-content/uploads/2018/09/map-pointer.png',
  iconSize: [20,20]
})



function App() {
  return (
    <div className="App">
      <LeafletMap className="leaflet-map" center={[12.971389, 77.750130]} zoom="12">
        <TileLayer attribution={'&copy; <a href="http://osm.org/copyright">OpenStreetMap</a> contributors'} url={"http://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png"} />
        <Marker position={[12.971389, 77.750130]} icon={newIcon}>
        <Popup>
          pop
        </Popup>
        </Marker>
        <Marker position={[12.871389, 77.750130]} icon={newIcon}>
        <Popup>
          pop
        </Popup>
        </Marker>        
      </LeafletMap>
    </div>
  );
}

const rootElement = document.getElementById("root");
ReactDOM.render(<App />, rootElement);
