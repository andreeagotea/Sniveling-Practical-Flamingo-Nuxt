<template>
  <div class="content-list4-container thq-section-padding">
    <div class="content-list4-max-width thq-section-max-width thq-flex-column">
      <div class="content-list4-content thq-flex-column">
        <ul class="content-list4-ul thq-flex-column">
          <li class="content-list4-li list-item thq-flex-column">
            <h2 class="content-list4-heading7 thq-heading-2">{{ heading7 }}</h2>
            <p class="content-list4-content7 thq-body-small">{{ content7 }}</p>
            <ul class="content-list4-ul1 thq-flex-column">
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
      <div class="content-list4-content1 thq-body-small">
        <ul class="content-list4-ul2 thq-flex-column">
          <li class="content-list4-li03 list-item thq-flex-column">
            <h2 class="content-list4-heading1 thq-heading-2">{{ heading1 }}</h2>
            <p>{{ content1 }}</p>
            <ul class="content-list4-ul3 thq-flex-column">
              <li class="list-item">
                <h3 class="thq-heading-3">{{ heading2 }}</h3>
                <p>{{ content2 }}</p>
              </li>
              <li class="list-item">
                <h3 class="thq-heading-3">{{ heading3 }}</h3>
                <p class="thq-body-small">{{ content3 }}</p>
              </li>
              <li class="list-item">
                <h3 class="thq-heading-3">{{ heading4 }}</h3>
                <p class="thq-body-small">{{ content4 }}</p>
              </li>
              <li class="list-item">
                <h3 class="thq-heading-3">{{ heading5 }}</h3>
                <p class="thq-body-small">{{ content5 }}</p>
              </li>
              <li class="list-item">
                <h3 class="thq-heading-3">{{ heading6 }}</h3>
                <p class="thq-body-small">{{ content6 }}</p>
              </li>
            </ul>
          </li>
        </ul>
      </div>
      <div class="content-list4-content2 thq-flex-column">
        <ul class="content-list4-ul4 thq-flex-column">
          <li class="content-list4-li09 list-item thq-flex-column">
            <h2 class="content-list4-heading10 thq-heading-2">{{ heading10 }}</h2>
            <p class="content-list4-content10 thq-body-small">{{ content10 }}</p>
            <ul class="content-list4-ul5 thq-flex-column">
              <li class="list-item">
                <h3 class="thq-heading-3">{{ heading11 }}</h3>
                <p class="thq-body-small">{{ content11 }}</p>
              </li>
              <li class="list-item">
                <h3 class="thq-heading-3">{{ heading12 }}</h3>
                <p class="thq-body-small">{{ content12 }}</p>
              </li>
              <li class="list-item">
                <h3 class="thq-heading-3">{{ heading13 }}</h3>
                <p class="thq-body-small">{{ content13 }}</p>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContentList4',
  props: {
    heading4: {
      type: String,
      default: 'Data Collection',
    },
    heading9: {
      type: String,
      default: 'Products and Services',
    },
    content3: {
      type: String,
      default:
        'Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Mauris vitae ultricies est.',
    },
    content12: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Est vitae blanditiis ab aliquam tempore aut ipsam iusto in sunt repellat ex voluptatum inventore ab facilis galisum ea consequatur consequuntur. Ab voluptas voluptatem eum consequatur aspernatur non laboriosam atque est labore asperiores a neque quos.  Ea nemo modi hic dicta saepe et veritatis maiores At praesentium aliquid. Sed dolores architecto non doloribus quia eos consectetur commodi non tenetur vitae est neque omnis.  Non perspiciatis velit At aliquam rerum ut officiis ipsa id minima eius ut sapiente nobis et nemo neque. Aut maiores tempora in officiis sunt eum voluptatem tenetur sit iste reprehenderit ea nisi dolor. Ea impedit omnis ad internos autem ut esse sunt ad saepe maiores vel perferendis veritatis. Ex magni fugiat ut reprehenderit laudantium sit galisum ipsam eos tempora doloribus sed accusantium nobis eum praesentium quod.',
    },
    content9: {
      type: String,
      default:
        'Curabitur auctor semper purus, at tincidunt libero vestibulum sit amet.',
    },
    content7: {
      type: String,
      default:
        'Donec non felis at nulla fringilla tincidunt. Sed ac mauris id mi efficitur ultricies.',
    },
    content2: {
      type: String,
      default:
        'Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.',
    },
    heading11: {
      type: String,
      default: 'General',
    },
    content6: {
      type: String,
      default:
        'Integer nec elit sit amet nunc pellentesque fringilla. Ut auctor, libero vel aliquet molestie, velit eros consequat justo.',
    },
    heading6: {
      type: String,
      default: 'Cookies',
    },
    heading8: {
      type: String,
      default: 'Campaign Tracking',
    },
    content5: {
      type: String,
      default:
        'Fusce auctor sapien nec odio tincidunt, vitae tincidunt purus lacinia.',
    },
    content1: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla eget libero nec justo ultricies aliquam.',
    },
    heading3: {
      type: String,
      default: 'Refund Policy',
    },
    heading2: {
      type: String,
      default: 'Privacy Statement',
    },
    content13: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Est vitae blanditiis ab aliquam tempore aut ipsam iusto in sunt repellat ex voluptatum inventore ab facilis galisum ea consequatur consequuntur. Ab voluptas voluptatem eum consequatur aspernatur non laboriosam atque est labore asperiores a neque quos.  Ea nemo modi hic dicta saepe et veritatis maiores At praesentium aliquid. Sed dolores architecto non doloribus quia eos consectetur commodi non tenetur vitae est neque omnis.  Non perspiciatis velit At aliquam rerum ut officiis ipsa id minima eius ut sapiente nobis et nemo neque. Aut maiores tempora in officiis sunt eum voluptatem tenetur sit iste reprehenderit ea nisi dolor. Ea impedit omnis ad internos autem ut esse sunt ad saepe maiores vel perferendis veritatis. Ex magni fugiat ut reprehenderit laudantium sit galisum ipsam eos tempora doloribus sed accusantium nobis eum praesentium quod.',
    },
    heading13: {
      type: String,
      default: 'Refunds',
    },
    content11: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Nam nihil facilis sit consequuntur internos qui minima rerum ut molestias laudantium aut iusto deserunt. Aut voluptatibus excepturi qui officia laudantium est repellendus tempore hic sunt debitis.  Ut galisum tempore in enim fugit eum pariatur possimus est tenetur nemo et sint sint et dolores Quis. Aut illum perspiciatis rem architecto culpa et fuga aliquid. Est omnis praesentium ut nisi internos rem quod totam et similique quis. Est tempore cumque aut recusandae labore qui error molestiae et possimus quia!  Eum Quis asperiores non nihil tempora qui quia voluptatem aut aspernatur aspernatur aut asperiores labore et sapiente quaerat qui suscipit quia. Ea nesciunt iste aut temporibus culpa sit dignissimos quaerat eum architecto voluptatum et nemo velit At harum harum.',
    },
    heading12: {
      type: String,
      default: 'Damages and issues',
    },
    content4: {
      type: String,
      default:
        'Sed euismod justo nec nisi ullamcorper, sit amet fermentum justo ultricies.',
    },
    heading1: {
      type: String,
      default: 'Terms of Service',
    },
    heading7: {
      type: String,
      default: 'Sharing Data with Third Parties',
    },
    heading10: {
      type: String,
      default: 'Refund Policy',
    },
    content10: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Vel dolores illum est aperiam quis nam voluptatem quia et omnis autem qui dolore ullam sed fugiat cumque! Qui accusamus assumenda et molestias eius et error sunt. Id recusandae nostrum ea officiis voluptatem in nisi consequatur sed quia tenetur sit alias molestias qui illum soluta.  Est nesciunt perferendis eum sint rerum 33 cupiditate dolorem id corrupti laboriosam ut debitis veniam ut ipsam fugit vel sunt consequatur. Et nobis quasi et cumque adipisci aut molestiae eligendi quo inventore dicta ea suscipit sequi sed veritatis nemo.',
    },
    heading5: {
      type: String,
      default: 'Data Usage',
    },
  },
}
</script>

<style scoped>
.content-list4-container {
  width: 100%;
  height: auto;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.content-list4-max-width {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  flex-direction: column;
}
.content-list4-content {
  align-self: stretch;
  align-items: flex-start;
}
.content-list4-ul {
  align-items: flex-start;
}
.content-list4-li {
  align-items: flex-start;
}
.content-list4-heading7 {
  align-self: center;
  text-align: center;
}
.content-list4-content7 {
  margin-bottom: var(--dl-space-space-halfunit);
}
.content-list4-ul1 {
  align-items: flex-start;
  padding-left: var(--dl-space-space-fiveunits);
}
.content-list4-content1 {
  align-self: stretch;
  align-items: flex-start;
}
.content-list4-ul2 {
  align-items: flex-start;
}
.content-list4-li03 {
  align-items: flex-start;
}
.content-list4-heading1 {
  align-self: center;
  text-align: center;
}
.content-list4-content1 {
  margin-bottom: var(--dl-space-space-halfunit);
}
.content-list4-ul3 {
  align-items: flex-start;
  padding-left: var(--dl-space-space-fiveunits);
}
.content-list4-content2 {
  align-self: stretch;
  align-items: flex-start;
}
.content-list4-ul4 {
  align-items: flex-start;
}
.content-list4-li09 {
  align-items: flex-start;
}
.content-list4-heading10 {
  align-self: center;
  text-align: center;
}
.content-list4-content10 {
  margin-bottom: var(--dl-space-space-halfunit);
}
.content-list4-ul5 {
  align-items: flex-start;
  padding-left: var(--dl-space-space-fiveunits);
}
@media(max-width: 767px) {
  .content-list4-ul1 {
    padding-left: var(--dl-space-space-threeunits);
  }
  .content-list4-ul3 {
    padding-left: var(--dl-space-space-threeunits);
  }
  .content-list4-ul5 {
    padding-left: var(--dl-space-space-threeunits);
  }
}
@media(max-width: 479px) {
  .content-list4-ul1 {
    padding-left: var(--dl-space-space-oneandhalfunits);
  }
  .content-list4-ul3 {
    padding-left: var(--dl-space-space-oneandhalfunits);
  }
  .content-list4-ul5 {
    padding-left: var(--dl-space-space-oneandhalfunits);
  }
}
</style>
