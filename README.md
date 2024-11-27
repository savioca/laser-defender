<h1 align="center">2D Game</h1>
<p align="center">Project <strong>Laser Defender</strong> developed in 2020</p>


<p align="center">
  <a href="https://dotnet.microsoft.com/pt-br/learn/csharp/">
    <img height="25em" alt="C#" src="https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white"/>
  </a>
  <a aria-label="Unity" href="https://github.com/facebook/react/blob/master/CHANGELOG.md#16120-november-14-2019">
    <img src="https://img.shields.io/badge/Made%20with-Unity-57b9d3.svg?style=for-the-badge&logo=unity"></img>
  </a>
  <img src="Assets/laserdefender.png" align="center"></img>
<br>
  <img src="Assets/laserdefendergp.png" align="center"></img>
</p>

## :rocket: Technologies

<table>
  <thead>
    <th>Back-end</th>
    <th>Front-end</th>
    <th>Mobile</th>
  </thead>
  <tbody>
    <tr>
      <td>Node.js</td>
      <td>ReactJS</td>
      <td>React Native - Expo</td>
    </tr>
    <tr>
      <td>MongoDB</td>
      <td>Axios</td>
      <td>Axios</td>
    </tr>
    <tr>
      <td>Nodemon</td>
      <td>React Hooks</td>
      <td>React Hooks</td>
    </tr>
    <tr>
      <td>Cors</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <td>Mongoose</td>
      <td>-</td>
      <td>-</td>
    </tr>
  </tbody>
</table>

## Setup
To install the dependencies and to execute the **Backend**, clone the project on your computer an execute:
```bash
cd backend
npm install
npm start
```
To run the React's **Frontend** use:
```bash
cd frontend
npm install
npm start
```
When the process end, automatically will open the page `localhost:3000` on your web browser with de Project Be The Hero.

To test the React Native **Mobile**, first put your server address (your computer) in the file`src/services/api.js`, and after execute the commands:
```bash
# Don't execute the following line if tou have the Expo (CLI) already intalled! 
yarn global add install expo-cli

cd mobile
npm install
npm start
```
When the proccess end, automatically will open the page `localhost:19002`. Connect your emulator, or test the app by `LAN`: Download the *Expo* app from Play Store or App Store and scan the QR Code.
