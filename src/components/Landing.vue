<template>
  <v-card elevation="5" dark>
    <v-tabs vertical background-color="pink" centered center-active>
      <v-tabs-slider color="white"></v-tabs-slider>
      <v-tab>
        <v-icon left>mdi-magnify</v-icon>
        Identifica
      </v-tab>
      <v-tab>
        <v-icon left>mdi-account</v-icon>
        Resiste
      </v-tab>
      <v-tab>
        <v-icon left>mdi-access-point</v-icon>
        Denuncia
      </v-tab>
      <v-tab-item transition="fade-transition">
        <v-card flat>
          <v-card-text>
            <h1 class="pink--text text-uppercase">¿Qué es la violencia de género en línea?</h1>
            <p class="mt-5 mb-5 text-justify">
              La violencia de género en línea (VGL) o violencia de género digital son conceptos que usamos para referirnos a acciones violentas en
              Internet, que han sido motivadas por creencias y/o actitudes discriminatorias basadas en el género. Este tipo de violencia se comete o
              agrava por el uso de tecnologías de la información y comunicación. Es tan real como cualquier otro tipo de violencia y causa daño
              físico, psicológico y/o sexual.
            </p>
            <h1 class="pink--text text-uppercase">Efectos de la violencia en línea</h1>
            <p class="mt-5 mb-0 justify-center">
              Afecta a las mujeres de maneras muy profundas. Las agresiones que se manifiestan en el mundo virtual, además de vulnerar los derechos de
              miles de mujeres y cuerpos disidentes que usan internet, también decantan en experiencias de violencia: desde amenazas de violencia
              física hasta daño psicológico.
            </p>
          </v-card-text>
        </v-card>
      </v-tab-item>
      <v-tab-item transition="fade-transition">
        <v-card flat>
          <v-card-text>
            <h1 class="pink--text text-uppercase">¿Qué es la seguridad digital?</h1>
            <p class="mt-5 mb-5 text-justify">
              Definimos a la seguridad digital como el conjunto de hábitos y decisiones que tomamos para mitigar riesgos asociados al uso de la
              tecnología. Por si no lo notaste, esta definición no se enfoca en la tecnología, sino en el uso que le damos y las decisiones que
              tomamos alrededor de ella según nuestro contexto y necesidades. Por eso, aprender sobre seguridad digital implica crear nuevos hábitos,
              construir nuevos conocimientos y así, tomar decisiones enfocadas en la privacidad y la seguridad. Es una invitación a repensar nuestra
              relación con Internet.
            </p>
            <h1 class="pink--text text-uppercase">Sexting Seguro</h1>
            <p class="mt-5 mb-0 justify-center">
              La tecnología nos ha permitido nuevas formas de relacionarnos sexual y/o afectivamente. Una de estas formas es el sexting, práctica por
              la que enviamos y recibimos texto, fotos, audios y videos sexualmente explícitos con previo consentimiento. Para ello, usamos
              aplicaciones de mensajería instantánea como: Instagram, WhatsApp, Telegram, Facebook Messenger, entre otras.
            </p>
            <p class="mt-5 mb-0 justify-center">
              Para sextear, ten presente que la palabra clave es el <strong>consentimiento</strong>. El enviar una imagen, un audio o un video es una
              decisión que debes tomar de manera libre, sin presiones ni amenazas. Además, quien reciba este material debe manifestar su deseo de
              querer recibirlas y entre ustedes generar compromisos de privacidad, seguridad y conservación del material íntimo. Así, respetando el
              consentimiento, el sexting puede ser una práctica saludable para nuestra sexualidad. De lo contrario, puede traernos muchos riesgos.
            </p>
          </v-card-text>
        </v-card>
      </v-tab-item>
      <v-tab-item transition="fade-transition">
        <v-card flat>
          <v-card-text>
            <h1 class="pink--text text-uppercase">Cuando no hay consenso</h1>
            <p class="mt-5 mb-5 text-justify">
              La violencia de género en internet es un <strong>delito</strong>. Aquí te brindamos información para que puedas denunciar tu caso y
              ejercer tus derechos.
            </p>
            <h1 class="pink--text text-uppercase">Quiero Denunciar</h1>
            <p class="mt-5 justify-center">
              Desde Septiembre del 2018, en el Perú la violencia en internet es delito, pero muchas personas aún no saben cuales son los pasos para
              denunciar. Si alguna vez te has preguntado: ¿Debo ir a la comisaría o al Ministerio Público?, ¿Debo contratar una abogada? o ¿Qué cuenta
              como evidencia en estos casos?, en esta sección buscamos resolver tus dudas.
            </p>
            <h1 class="pink--text text-uppercase">Necesito Evidencia</h1>
            <p class="mt-5 mb-0 justify-center">
              Recoger evidencia es un paso muy importante para tu denuncia. Inclusive si aún no estás segura si quieres denunciar, te recomendamos que
              empieces a capturar la evidencia en caso quieras hacerlo más adelante. Si no estás segura si quieres denunciar te recomendamos que tomes
              la decisión que sea mejor para ti. Puede ser un proceso difícil y hay varios factores a tomar en cuenta. Recuerda: Nadie puede
              obligarte.
            </p>
          </v-card-text>
        </v-card>
      </v-tab-item>
    </v-tabs>
  </v-card>
</template>
<script>
  export default {
    name: "Landing",
  };
</script>
