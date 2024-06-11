<template>
  <div class="features8-layout226 thq-section-padding">
    <div class="features8-max-width thq-section-max-width thq-grid-auto-300">
      <div class="thq-flex-column">
        <span class="thq-body-small">{{ feature1Slogan }}</span>
        <div class="thq-flex-column features8-content">
          <h3 class="features8-title1 thq-heading-3">{{ feature1Title }}</h3>
          <span class="features8-description1 thq-body-small">
            {{ feature1Description }}
          </span>
        </div>
        <div class="features8-actions thq-flex-row">
          <button class="features8-button thq-button-filled">
            <span class="features8-action1 thq-body-small">{{ mainAction }}</span>
          </button>
          <button class="features8-button1 thq-button-outline">
            <span class="features8-action2 thq-body-small">
              {{ secondaryAction }}
            </span>
          </button>
        </div>
      </div>
      <div class="thq-flex-column">
        <span class="thq-body-small">{{ feature2Slogan }}</span>
        <div class="thq-flex-column features8-content1">
          <h3 class="features8-title11 thq-heading-3">{{ feature2Title }}</h3>
          <span class="features8-description11 thq-body-small">
            {{ feature2Description }}
          </span>
        </div>
        <div class="features8-actions1 thq-flex-row">
          <button class="features8-button2 thq-button-filled">
            <span class="features8-action11 thq-body-small">
              {{ mainAction }}
            </span>
          </button>
          <button class="features8-button3 thq-button-outline">
            <span class="features8-action21 thq-body-small">
              {{ secondaryAction }}
            </span>
          </button>
        </div>
      </div>
      <div class="thq-flex-column">
        <span class="thq-body-small">{{ feature3Slogan }}</span>
        <div class="thq-flex-column features8-content2">
          <h3 class="features8-title12 thq-heading-3">{{ feature3Title }}</h3>
          <span class="features8-description12 thq-body-small">
            {{ feature3Description }}
          </span>
        </div>
        <div class="features8-actions2 thq-flex-row">
          <button class="features8-button4 thq-button-filled">
            <span class="features8-action12 thq-body-small">
              {{ mainAction }}
            </span>
          </button>
          <button class="features8-button5 thq-button-outline">
            <span class="features8-action22 thq-body-small">
              {{ secondaryAction }}
            </span>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Features8',
  props: {
    feature2Title: {
      type: String,
      default: 'Privacy Statement',
    },
    secondaryAction: {
      type: String,
      default: 'View Refund Policy',
    },
    feature3Slogan: {
      type: String,
      default: 'Refund policy details',
    },
    feature2Slogan: {
      type: String,
      default: 'Privacy is our priority',
    },
    feature1Description: {
      type: String,
      default: 'Detailed information on terms of service',
    },
    feature3Description: {
      type: String,
      default: 'Explore our refund policy',
    },
    feature1Title: {
      type: String,
      default: 'Terms of Service',
    },
    feature3Title: {
      type: String,
      default: 'Refund Policy',
    },
    feature2Description: {
      type: String,
      default: 'Learn about our commitment to privacy',
    },
    mainAction: {
      type: String,
      default: 'Read Terms of Service',
    },
    feature1Slogan: {
      type: String,
      default: 'Understand our terms of service',
    },
  },
}
</script>

<style scoped>
.features8-layout226 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: row;
  justify-content: center;
}
.features8-max-width {
  align-self: flex-start;
}
.features8-title1 {
  text-align: center;
}
.features8-description1 {
  text-align: center;
}
.features8-actions {
  gap: var(--dl-space-space-unit);
  flex-wrap: wrap;
}
.features8-button {
  flex: 1;
}
.features8-action1 {
  text-align: center;
}
.features8-button1 {
  flex: 1;
}
.features8-action2 {
  text-align: center;
}
.features8-title11 {
  text-align: center;
}
.features8-description11 {
  text-align: center;
}
.features8-actions1 {
  gap: var(--dl-space-space-unit);
  flex-wrap: wrap;
}
.features8-button2 {
  flex: 1;
}
.features8-action11 {
  text-align: center;
}
.features8-button3 {
  flex: 1;
}
.features8-action21 {
  text-align: center;
}
.features8-title12 {
  text-align: center;
}
.features8-description12 {
  text-align: center;
}
.features8-actions2 {
  gap: var(--dl-space-space-unit);
  flex-wrap: wrap;
}
.features8-button4 {
  flex: 1;
}
.features8-action12 {
  text-align: center;
}
.features8-button5 {
  flex: 1;
}
.features8-action22 {
  text-align: center;
}
@media(max-width: 991px) {
  .features8-layout226 {
    flex-direction: column;
  }
  .features8-content {
    align-items: center;
  }
  .features8-content1 {
    align-items: center;
  }
  .features8-content2 {
    align-items: center;
  }
}
@media(max-width: 479px) {
  .features8-button {
    width: 100%;
  }
  .features8-button1 {
    width: 100%;
  }
  .features8-button2 {
    width: 100%;
  }
  .features8-button3 {
    width: 100%;
  }
  .features8-button4 {
    width: 100%;
  }
  .features8-button5 {
    width: 100%;
  }
}
</style>
