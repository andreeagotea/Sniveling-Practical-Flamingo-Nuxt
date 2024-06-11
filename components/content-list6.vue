<template>
  <div class="content-list6-container thq-section-padding">
    <div class="content-list6-max-width thq-section-max-width">
      <div class="content-list6-container1 thq-flex-column">
        <button
          @click="handleButtonClick"
          v-if="isTermsVisible"
          class="thq-button-filled"
        >
          {{ button }}
        </button>
        <button
          @click="handleButtonClick"
          v-if="!isTermsVisible"
          class="thq-button-outline"
        >
          {{ button }}
        </button>
        <button
          @click="handleButtonClick"
          v-if="!isPrivacyVisible"
          class="thq-button-outline"
        >
          {{ button1 }}
        </button>
        <button
          @click="handleButtonClick"
          v-if="isPrivacyVisible"
          class="thq-button-filled"
        >
          {{ button1 }}
        </button>
        <button
          @click="handleButtonClick"
          v-if="!isRefundVisible"
          class="thq-button-outline"
        >
          {{ button2 }}
        </button>
        <button
          @click="handleButtonClick"
          v-if="isRefundVisible"
          class="thq-button-filled"
        >
          {{ button2 }}
        </button>
      </div>
      <div class="content-list6-container2 thq-flex-column">
        <div v-if="isTermsVisible" class="content-list6-container3">
          <ul class="content-list6-ul thq-flex-column">
            <li class="content-list6-li list-item thq-flex-column">
              <h2 class="content-list6-heading7 thq-heading-2">{{ heading7 }}</h2>
              <p class="thq-body-small">{{ content7 }}</p>
              <ul class="content-list6-ul1 thq-flex-column">
                <li class="list-item">
                  <h3 class="thq-heading-3">{{ heading8 }}</h3>
                  <p class="thq-body-small">{{ content2 }}</p>
                </li>
                <li class="list-item">
                  <h3 class="thq-heading-3">{{ heading9 }}</h3>
                  <p class="thq-body-small">{{ content9 }}</p>
                </li>
              </ul>
            </li>
          </ul>
        </div>
        <div v-if="isPrivacyVisible" class="content-list6-container4">
          <ul class="thq-flex-column">
            <li class="content-list6-li03 list-item thq-flex-column">
              <h1 class="content-list6-heading1 thq-heading-2">{{ heading1 }}</h1>
              <span class="thq-body-small">{{ content1 }}</span>
              <ul class="content-list6-ul3 thq-flex-column">
                <li class="list-item">
                  <h1 class="thq-heading-3">{{ heading2 }}</h1>
                  <span class="thq-body-small">{{ content2 }}</span>
                </li>
                <li class="list-item">
                  <h1 class="thq-heading-3">{{ heading3 }}</h1>
                  <span class="thq-body-small">{{ content3 }}</span>
                </li>
                <li class="list-item">
                  <h1 class="thq-heading-3">{{ heading4 }}</h1>
                  <span class="thq-body-small">{{ content4 }}</span>
                </li>
                <li class="list-item">
                  <h1 class="thq-heading-3">{{ heading5 }}</h1>
                  <span class="thq-body-small">{{ content5 }}</span>
                </li>
                <li class="list-item">
                  <h1 class="thq-heading-3">{{ heading6 }}</h1>
                  <span class="thq-body-small">{{ content6 }}</span>
                </li>
              </ul>
            </li>
          </ul>
        </div>
        <div v-if="isRefundVisible" class="content-list6-container5">
          <ul class="content-list6-ul4 thq-flex-column">
            <li class="content-list6-li09 list-item thq-flex-column">
              <h1 class="content-list6-heading10 thq-heading-2">
                {{ heading10 }}
              </h1>
              <span class="thq-body-small">{{ content10 }}</span>
              <ul class="content-list6-ul5 thq-flex-column">
                <li class="list-item">
                  <h1 class="thq-heading-3">{{ heading11 }}</h1>
                  <span class="thq-body-small">{{ content11 }}</span>
                </li>
                <li class="list-item">
                  <h1 class="thq-heading-3">{{ heading12 }}</h1>
                  <span class="thq-body-small">{{ content12 }}</span>
                </li>
                <li class="list-item">
                  <h1 class="thq-heading-3">{{ heading13 }}</h1>
                  <span class="thq-body-small">{{ content13 }}</span>
                </li>
              </ul>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContentList6',
  props: {
    heading7: {
      type: String,
      default: 'Terms of service',
    },
    content9: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Est vitae blanditiis ab aliquam tempore aut ipsam iusto in sunt repellat ex voluptatum inventore ab facilis galisum ea consequatur consequuntur. Ab voluptas voluptatem eum consequatur aspernatur non laboriosam atque est labore asperiores a neque quos.  Ea nemo modi hic dicta saepe et veritatis maiores At praesentium aliquid. Sed dolores architecto non doloribus quia eos consectetur commodi non tenetur vitae est neque omnis.  Non perspiciatis velit At aliquam rerum ut officiis ipsa id minima eius ut sapiente nobis et nemo neque. Aut maiores tempora in officiis sunt eum voluptatem tenetur sit iste reprehenderit ea nisi dolor. Ea impedit omnis ad internos autem ut esse sunt ad saepe maiores vel perferendis veritatis. Ex magni fugiat ut reprehenderit laudantium sit galisum ipsam eos tempora doloribus sed accusantium nobis eum praesentium quod.',
    },
    content4: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Id galisum officiis rem quod internos qui provident quaerat hic minus eveniet est officiis galisum sit rerum dignissimos. Sit voluptatem alias et veniam rerum ea quod ipsam ut quam neque est nihil repellat est aspernatur voluptatem est voluptas ratione?  Ea vero tempore At soluta temporibus 33 galisum excepturi quo modi distinctio. Qui dolor soluta sit ipsam vitae et suscipit molestiae est consequatur galisum aut sapiente voluptatem sed quas eaque et minima minus?  Rem soluta consequatur et velit cupiditate sed eligendi laudantium rem pariatur galisum sit mollitia debitis eum delectus ipsum aut consequatur mollitia. Qui voluptatibus molestias ut totam Quis ea unde dolorem sit animi eveniet et galisum explicabo. Est culpa error ut voluptatibus voluptatem qui dignissimos dolorem quo laborum distinctio qui omnis perspiciatis ab facilis temporibus qui perspiciatis consectetur. Ab praesentium fugiat eos veritatis quam ex modi autem et sapiente dolorem?',
    },
    heading10: {
      type: String,
      default: 'Refund Policy',
    },
    button1: {
      type: String,
      default: 'Privacy statement',
    },
    heading9: {
      type: String,
      default: 'Products and Services',
    },
    heading2: {
      type: String,
      default: 'Types of data we collect',
    },
    heading13: {
      type: String,
      default: 'Refunds',
    },
    content5: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Ut cumque cupiditate eos perferendis tempora et ullam quis qui fugiat necessitatibus qui quia dolorem 33 earum reprehenderit eum rerum blanditiis. Et vitae distinctio 33 magni ratione ut odit rerum est nihil error et minus dolor quo harum fugiat. Eos quam assumenda id fugit optio aut magni sunt!  Ut iure aliquam vel velit modi sit voluptatibus atque ut corporis sint sit omnis enim a pariatur officiis aut nulla voluptate. In facere incidunt aut sapiente maxime qui quibusdam facilis non officia consectetur sit laboriosam libero aut cupiditate possimus ut sunt reiciendis. Et repudiandae magnam aut quaerat ipsam aut repellat laboriosam. Ab facilis deleniti ut voluptas molestiae sed omnis maiores ut aliquid culpa vel nesciunt saepe.  Aut placeat aspernatur aut alias nihil vel neque recusandae et corrupti accusantium ab quod temporibus ut nulla eaque et magnam nemo. Ad sunt minus rem earum delectus hic officia iste qui sunt quos non officiis illo vel doloribus perspiciatis. Ab soluta eius sed quidem dolores rem necessitatibus minus 33 minus commodi. Nam repudiandae libero non laboriosam voluptate et saepe fuga vel repudiandae pariatur aut assumenda illo.',
    },
    heading3: {
      type: String,
      default: 'How we use your data',
    },
    heading11: {
      type: String,
      default: 'General',
    },
    content12: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Est vitae blanditiis ab aliquam tempore aut ipsam iusto in sunt repellat ex voluptatum inventore ab facilis galisum ea consequatur consequuntur. Ab voluptas voluptatem eum consequatur aspernatur non laboriosam atque est labore asperiores a neque quos.  Ea nemo modi hic dicta saepe et veritatis maiores At praesentium aliquid. Sed dolores architecto non doloribus quia eos consectetur commodi non tenetur vitae est neque omnis.  Non perspiciatis velit At aliquam rerum ut officiis ipsa id minima eius ut sapiente nobis et nemo neque. Aut maiores tempora in officiis sunt eum voluptatem tenetur sit iste reprehenderit ea nisi dolor. Ea impedit omnis ad internos autem ut esse sunt ad saepe maiores vel perferendis veritatis. Ex magni fugiat ut reprehenderit laudantium sit galisum ipsam eos tempora doloribus sed accusantium nobis eum praesentium quod.',
    },
    heading6: {
      type: String,
      default: 'Cookies',
    },
    heading12: {
      type: String,
      default: 'Damages and issues',
    },
    heading4: {
      type: String,
      default: 'Sharing your data with 3rd parties',
    },
    heading5: {
      type: String,
      default: 'Campaign tracking',
    },
    content11: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Nam nihil facilis sit consequuntur internos qui minima rerum ut molestias laudantium aut iusto deserunt. Aut voluptatibus excepturi qui officia laudantium est repellendus tempore hic sunt debitis.  Ut galisum tempore in enim fugit eum pariatur possimus est tenetur nemo et sint sint et dolores Quis. Aut illum perspiciatis rem architecto culpa et fuga aliquid. Est omnis praesentium ut nisi internos rem quod totam et similique quis. Est tempore cumque aut recusandae labore qui error molestiae et possimus quia!  Eum Quis asperiores non nihil tempora qui quia voluptatem aut aspernatur aspernatur aut asperiores labore et sapiente quaerat qui suscipit quia. Ea nesciunt iste aut temporibus culpa sit dignissimos quaerat eum architecto voluptatum et nemo velit At harum harum.',
    },
    content1: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Vel dolores illum est aperiam quis nam voluptatem quia et omnis autem qui dolore ullam sed fugiat cumque! Qui accusamus assumenda et molestias eius et error sunt. Id recusandae nostrum ea officiis voluptatem in nisi consequatur sed quia tenetur sit alias molestias qui illum soluta.  Est nesciunt perferendis eum sint rerum 33 cupiditate dolorem id corrupti laboriosam ut debitis veniam ut ipsam fugit vel sunt consequatur. Et nobis quasi et cumque adipisci aut molestiae eligendi quo inventore dicta ea suscipit sequi sed veritatis nemo.',
    },
    content7: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Vel dolores illum est aperiam quis nam voluptatem quia et omnis autem qui dolore ullam sed fugiat cumque! Qui accusamus assumenda et molestias eius et error sunt. Id recusandae nostrum ea officiis voluptatem in nisi consequatur sed quia tenetur sit alias molestias qui illum soluta.  Est nesciunt perferendis eum sint rerum 33 cupiditate dolorem id corrupti laboriosam ut debitis veniam ut ipsam fugit vel sunt consequatur. Et nobis quasi et cumque adipisci aut molestiae eligendi quo inventore dicta ea suscipit sequi sed veritatis nemo.',
    },
    content13: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Est vitae blanditiis ab aliquam tempore aut ipsam iusto in sunt repellat ex voluptatum inventore ab facilis galisum ea consequatur consequuntur. Ab voluptas voluptatem eum consequatur aspernatur non laboriosam atque est labore asperiores a neque quos.  Ea nemo modi hic dicta saepe et veritatis maiores At praesentium aliquid. Sed dolores architecto non doloribus quia eos consectetur commodi non tenetur vitae est neque omnis.  Non perspiciatis velit At aliquam rerum ut officiis ipsa id minima eius ut sapiente nobis et nemo neque. Aut maiores tempora in officiis sunt eum voluptatem tenetur sit iste reprehenderit ea nisi dolor. Ea impedit omnis ad internos autem ut esse sunt ad saepe maiores vel perferendis veritatis. Ex magni fugiat ut reprehenderit laudantium sit galisum ipsam eos tempora doloribus sed accusantium nobis eum praesentium quod.',
    },
    content3: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Est vitae blanditiis ab aliquam tempore aut ipsam iusto in sunt repellat ex voluptatum inventore ab facilis galisum ea consequatur consequuntur. Ab voluptas voluptatem eum consequatur aspernatur non laboriosam atque est labore asperiores a neque quos.  Ea nemo modi hic dicta saepe et veritatis maiores At praesentium aliquid. Sed dolores architecto non doloribus quia eos consectetur commodi non tenetur vitae est neque omnis.  Non perspiciatis velit At aliquam rerum ut officiis ipsa id minima eius ut sapiente nobis et nemo neque. Aut maiores tempora in officiis sunt eum voluptatem tenetur sit iste reprehenderit ea nisi dolor. Ea impedit omnis ad internos autem ut esse sunt ad saepe maiores vel perferendis veritatis. Ex magni fugiat ut reprehenderit laudantium sit galisum ipsam eos tempora doloribus sed accusantium nobis eum praesentium quod.',
    },
    button: {
      type: String,
      default: 'Terms of service',
    },
    content10: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Vel dolores illum est aperiam quis nam voluptatem quia et omnis autem qui dolore ullam sed fugiat cumque! Qui accusamus assumenda et molestias eius et error sunt. Id recusandae nostrum ea officiis voluptatem in nisi consequatur sed quia tenetur sit alias molestias qui illum soluta.  Est nesciunt perferendis eum sint rerum 33 cupiditate dolorem id corrupti laboriosam ut debitis veniam ut ipsam fugit vel sunt consequatur. Et nobis quasi et cumque adipisci aut molestiae eligendi quo inventore dicta ea suscipit sequi sed veritatis nemo.',
    },
    content6: {
      type: String,
      default:
        'Ut doloremque aliquam qui veniam deserunt sit voluptates iusto et unde quod ut quam unde ut nemo eius! Ut saepe consequuntur non quibusdam soluta aut maiores eaque et rerum error nam incidunt saepe aut nihil voluptatem. 33 nulla quaerat est doloremque voluptatem ut libero magnam id placeat aliquid. Ea minus totam est inventore minus sed temporibus aperiam At ratione maiores eum libero consequatur aut laborum exercitationem.',
    },
    button2: {
      type: String,
      default: 'Refund Policy',
    },
    heading8: {
      type: String,
      default: 'General Terms and Conditions',
    },
    heading1: {
      type: String,
      default: 'Privacy statement',
    },
    content2: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Nam nihil facilis sit consequuntur internos qui minima rerum ut molestias laudantium aut iusto deserunt. Aut voluptatibus excepturi qui officia laudantium est repellendus tempore hic sunt debitis.  Ut galisum tempore in enim fugit eum pariatur possimus est tenetur nemo et sint sint et dolores Quis. Aut illum perspiciatis rem architecto culpa et fuga aliquid. Est omnis praesentium ut nisi internos rem quod totam et similique quis. Est tempore cumque aut recusandae labore qui error molestiae et possimus quia!  Eum Quis asperiores non nihil tempora qui quia voluptatem aut aspernatur aspernatur aut asperiores labore et sapiente quaerat qui suscipit quia. Ea nesciunt iste aut temporibus culpa sit dignissimos quaerat eum architecto voluptatum et nemo velit At harum harum.',
    },
  },
  data() {
    return {
      isRefundVisible: false,
      isTermsVisible: true,
      isPrivacyVisible: false,
    }
  },
  methods: {
    handleButtonClick() {
      this.isRefundVisible = true
      this.isPrivacyVisible = false
      this.isTermsVisible = false
    },
  },
}
</script>

<style scoped>
.content-list6-container {
  width: 100%;
  height: auto;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.content-list6-max-width {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: flex-start;
  flex-direction: row;
}
.content-list6-container1 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: stretch;
  padding-top: var(--dl-space-space-threeunits);
  flex-direction: column;
  justify-content: center;
}
.content-list6-container2 {
  width: auto;
  padding: var(--dl-space-space-twounits);
  align-items: flex-start;
}
.content-list6-container3 {
  align-self: stretch;
  align-items: flex-start;
}
.content-list6-ul {
  align-items: flex-start;
}
.content-list6-li {
  align-items: flex-start;
}
.content-list6-heading7 {
  align-self: center;
  text-align: center;
}
.content-list6-ul1 {
  align-items: flex-start;
  padding-left: var(--dl-space-space-fiveunits);
}
.content-list6-container4 {
  align-self: stretch;
  align-items: flex-start;
}
.content-list6-li03 {
  align-items: flex-start;
}
.content-list6-heading1 {
  align-self: center;
  text-align: center;
}
.content-list6-ul3 {
  align-items: flex-start;
  padding-left: var(--dl-space-space-fiveunits);
}
.content-list6-container5 {
  align-self: stretch;
  align-items: flex-start;
}
.content-list6-ul4 {
  align-items: flex-start;
}
.content-list6-li09 {
  align-items: flex-start;
}
.content-list6-heading10 {
  align-self: center;
  text-align: center;
}
.content-list6-ul5 {
  align-items: flex-start;
  padding-left: var(--dl-space-space-fiveunits);
}
@media(max-width: 767px) {
  .content-list6-max-width {
    align-items: center;
    flex-direction: column;
  }
  .content-list6-container1 {
    align-self: center;
  }
  .content-list6-container2 {
    padding-left: 0px;
    padding-right: 0px;
  }
  .content-list6-ul1 {
    padding-left: var(--dl-space-space-threeunits);
  }
  .content-list6-ul3 {
    padding-left: var(--dl-space-space-threeunits);
  }
  .content-list6-ul5 {
    padding-left: var(--dl-space-space-threeunits);
  }
}
@media(max-width: 479px) {
  .content-list6-max-width {
    flex-direction: column;
  }
  .content-list6-container1 {
    align-self: center;
  }
  .content-list6-ul1 {
    padding-left: var(--dl-space-space-oneandhalfunits);
  }
  .content-list6-ul3 {
    padding-left: var(--dl-space-space-oneandhalfunits);
  }
  .content-list6-ul5 {
    padding-left: var(--dl-space-space-oneandhalfunits);
  }
}
</style>
