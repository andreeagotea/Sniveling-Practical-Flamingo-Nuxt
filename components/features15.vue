<template>
  <div class="features15-layout226 thq-section-padding">
    <img :alt="image1Alt" :src="image1Src" class="features15-image" />
    <div class="features15-max-width thq-section-max-width">
      <div class="features15-column">
        <svg viewBox="0 0 1243.4285714285713 1024" class="features15-icon">
          <path
            d="M365.714 932.571l219.429-109.714v-179.429l-219.429 93.714v195.429zM329.143 673.143l230.857-98.857-230.857-98.857-230.857 98.857zM950.857 932.571l219.429-109.714v-179.429l-219.429 93.714v195.429zM914.286 673.143l230.857-98.857-230.857-98.857-230.857 98.857zM658.286 505.714l219.429-94.286v-152l-219.429 93.714v152.571zM621.714 289.143l252-108-252-108-252 108zM1243.429 585.143v237.714c0 27.429-15.429 53.143-40.571 65.143l-256 128c-10.286 5.714-21.143 8-32.571 8s-22.286-2.286-32.571-8l-256-128c-1.714-0.571-2.857-1.143-4-2.286-1.143 1.143-2.286 1.714-4 2.286l-256 128c-10.286 5.714-21.143 8-32.571 8s-22.286-2.286-32.571-8l-256-128c-25.143-12-40.571-37.714-40.571-65.143v-237.714c0-29.143 17.714-55.429 44.571-67.429l248-106.286v-228.571c0-29.143 17.714-55.429 44.571-67.429l256-109.714c9.143-4 18.857-5.714 28.571-5.714s19.429 1.714 28.571 5.714l256 109.714c26.857 12 44.571 38.286 44.571 67.429v228.571l248 106.286c27.429 12 44.571 38.286 44.571 67.429z"
          ></path>
        </svg>
        <div class="features15-section-title">
          <span class="features15-over-title1 thq-body-small">
            {{ feature1Slogan }}
          </span>
          <div class="features15-content">
            <h3 class="features15-title1 thq-heading-3">{{ feature1Title }}</h3>
            <span class="features15-description1 thq-body-small">
              {{ feature1Description }}
            </span>
          </div>
          <div class="features15-actions">
            <button class="thq-button-filled features15-button">
              <span class="features15-action1 thq-body-small">
                {{ feature1Action1 }}
              </span>
            </button>
            <button class="thq-button-outline features15-button1">
              <span class="features15-action2 thq-body-small">
                {{ feature1Action2 }}
              </span>
            </button>
          </div>
        </div>
      </div>
      <div class="features15-column1">
        <svg viewBox="0 0 1243.4285714285713 1024" class="features15-icon2">
          <path
            d="M365.714 932.571l219.429-109.714v-179.429l-219.429 93.714v195.429zM329.143 673.143l230.857-98.857-230.857-98.857-230.857 98.857zM950.857 932.571l219.429-109.714v-179.429l-219.429 93.714v195.429zM914.286 673.143l230.857-98.857-230.857-98.857-230.857 98.857zM658.286 505.714l219.429-94.286v-152l-219.429 93.714v152.571zM621.714 289.143l252-108-252-108-252 108zM1243.429 585.143v237.714c0 27.429-15.429 53.143-40.571 65.143l-256 128c-10.286 5.714-21.143 8-32.571 8s-22.286-2.286-32.571-8l-256-128c-1.714-0.571-2.857-1.143-4-2.286-1.143 1.143-2.286 1.714-4 2.286l-256 128c-10.286 5.714-21.143 8-32.571 8s-22.286-2.286-32.571-8l-256-128c-25.143-12-40.571-37.714-40.571-65.143v-237.714c0-29.143 17.714-55.429 44.571-67.429l248-106.286v-228.571c0-29.143 17.714-55.429 44.571-67.429l256-109.714c9.143-4 18.857-5.714 28.571-5.714s19.429 1.714 28.571 5.714l256 109.714c26.857 12 44.571 38.286 44.571 67.429v228.571l248 106.286c27.429 12 44.571 38.286 44.571 67.429z"
          ></path>
        </svg>
        <div class="features15-section-title1">
          <span class="features15-over-title2 thq-body-small">
            {{ feature2Slogan }}
          </span>
          <div class="features15-content1">
            <h3 class="features15-title2 thq-heading-3">{{ feature2Title1 }}</h3>
            <span class="features15-description2 thq-body-small">
              {{ feature2Description1 }}
            </span>
          </div>
          <div class="features15-actions1">
            <button class="thq-button-filled features15-button2">
              <span class="features15-action11 thq-body-small">
                {{ feature2Action1 }}
              </span>
            </button>
            <button class="thq-button-outline features15-button3">
              <span class="features15-action21 thq-body-small">
                {{ feature2Action2 }}
              </span>
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features15',
  props: {
    feature1Action2: {
      type: String,
      default: 'Secondary action',
    },
    image1Alt: {
      type: String,
      default: 'Background image',
    },
    feature1Description: {
      type: String,
      default: 'Detailed information on terms of service',
    },
    feature1Slogan: {
      type: String,
      default: 'Understand our terms of service',
    },
    feature1Title: {
      type: String,
      default: 'Terms of Service',
    },
    feature2Action2: {
      type: String,
      default: 'Secondary action',
    },
    feature2Action1: {
      type: String,
      default: 'Main action',
    },
    feature1Action1: {
      type: String,
      default: 'Main action',
    },
    image1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1676907820153-2b61de2b9daf?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxODExMjY0MHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    feature2Description1: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    feature2Slogan: {
      type: String,
      default: 'Privacy is our priority',
    },
    feature2Title1: {
      type: String,
      default: 'Discover the Magic of Lorem Ipsum Text Generation',
    },
  },
}
</script>

<style scoped>
.features15-layout226 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: row;
  background-size: cover;
  justify-content: center;
}
.features15-image {
  top: 0px;
  left: 0px;
  right: 0px;
  width: 100%;
  bottom: 0px;
  height: 100%;
  position: absolute;
  object-fit: cover;
}
.features15-max-width {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  z-index: 100;
  align-items: center;
  flex-direction: row;
}
.features15-column {
  gap: var(--dl-space-space-oneandhalfunits);
  flex: 1;
  width: auto;
  display: flex;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.features15-icon {
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
}
.features15-section-title {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.features15-over-title1 {
  height: auto;
  font-size: 16px;
  font-style: normal;
  text-align: center;
  font-family: Roboto;
  font-weight: 600px;
  line-height: 150%;
  font-stretch: normal;
}
.features15-content {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.features15-title1 {
  text-align: center;
}
.features15-description1 {
  text-align: center;
}
.features15-actions {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-unit);
  padding-left: 0px;
  padding-right: 0px;
  padding-bottom: 0px;
}
.features15-action1 {
  text-align: center;
}
.features15-action2 {
  text-align: center;
}
.features15-column1 {
  gap: var(--dl-space-space-oneandhalfunits);
  flex: 1;
  width: auto;
  display: flex;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.features15-icon2 {
  width: var(--dl-size-size-small);
  height: var(--dl-size-size-small);
}
.features15-section-title1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.features15-over-title2 {
  height: auto;
  font-size: 16px;
  font-style: normal;
  text-align: center;
  font-family: Roboto;
  line-height: 150%;
  font-stretch: normal;
}
.features15-content1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.features15-title2 {
  text-align: center;
}
.features15-description2 {
  text-align: center;
}
.features15-actions1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-unit);
  padding-left: 0px;
  padding-right: 0px;
  padding-bottom: 0px;
}
.features15-action11 {
  text-align: center;
}
.features15-action21 {
  text-align: center;
}
@media(max-width: 991px) {
  .features15-layout226 {
    flex-direction: column;
  }
  .features15-content {
    align-items: center;
  }
  .features15-content1 {
    align-items: center;
  }
}
@media(max-width: 767px) {
  .features15-max-width {
    flex-direction: column;
  }
}
@media(max-width: 479px) {
  .features15-max-width {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .features15-actions {
    width: 100%;
    flex-direction: column;
  }
  .features15-button {
    width: 100%;
  }
  .features15-button1 {
    width: 100%;
  }
  .features15-actions1 {
    width: 100%;
    flex-direction: column;
  }
  .features15-button2 {
    width: 100%;
  }
  .features15-button3 {
    width: 100%;
  }
}
</style>
