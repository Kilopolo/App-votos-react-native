# App de Voto Electrónico

Esta es una aplicación de Voto Electrónico que permite a los ciudadanos registrarse, votar electrónicamente en elecciones y ver informes sobre los resultados de las elecciones. También proporciona información sobre los partidos políticos y candidatos registrados.

## Funcionalidades

La aplicación consta de las siguientes funcionalidades principales:

1. **Registro de Ciudadano**: Los ciudadanos pueden registrarse en la aplicación proporcionando información personal, como nombre, dirección, y número de identificación.

2. **Voto Electrónico**: Los ciudadanos registrados pueden emitir su voto en elecciones en curso de manera electrónica.

3. **Informe de la Elección**: La aplicación genera informes detallados sobre los resultados de las elecciones, incluyendo los votos emitidos y los ganadores.

4. **Visualización del Registro de Partidos y Candidatos**: Los usuarios pueden explorar información sobre los partidos políticos y candidatos registrados para tomar decisiones informadas antes de votar.

## 🚀 Instalación

1. Clona este repositorio:

```bash
git clone https://github.com/Kilopolo/App-votos-react-native.git
```

2. Instala las dependencias:

```bash
npm install
```

3. Configura Firebase:  
Crea un proyecto en Firebase y establece las credenciales en la aplicación para habilitar la autenticación y el almacenamiento de datos.


4. Inicia la aplicación en modo desarrollo:

```bash
npx expo start
```

---

## 📱 Probar la app en tu móvil

1. Instala la app **Expo Go**:
   - Android (Google Play): https://play.google.com/store/apps/details?id=host.exp.exponent  
   - iOS (App Store): https://apps.apple.com/app/expo-go/id982107779

2. Escanea el **código QR** que aparece en la terminal o en Metro Bundler cuando ejecutas `npx expo start`.

3. La app se abrirá automáticamente en tu móvil dentro de **Expo Go**.

4. (Opcional) También puedes abrirla en un emulador:
   - Android: presiona `a` en la terminal de Metro Bundler.
   - iOS (macOS): presiona `i` en la terminal de Metro Bundler.


## Tecnologías Utilizadas
React Native: Para el desarrollo de la interfaz de usuario de la aplicación móvil.
Firebase: Para la autenticación de usuarios y el almacenamiento de datos.
Base de Datos Firestore: Para almacenar los datos de elecciones, votos, partidos y candidatos.
Otros módulos de React Native: Para la navegación, estilos y funcionalidades adicionales.
Contribución
Si deseas contribuir a este proyecto, sigue estos pasos:

## Haz un fork del repositorio.
1. Crea una rama para tus cambios: 

   ```bash
   git checkout -b feature/nueva-funcionalidad.

2. Realiza tus cambios y asegúrate de que los tests pasen.
3. Haz un push de tus cambios: 

   ```bash
   git push origin feature/nueva-funcionalidad.

4. Crea un pull request en el repositorio original.

