> 官网: [https://haomo-tech.com](https://haomo-tech.com)

> 作者: 毫末科技

> 邮箱: hxg@haomo-studio.com

## 预览

![预览图片](http://downloads.haomo-tech.com/uniapp/hm-reply-card.png)

[在线效果预览](http://template.uniapp.haomo-tech.com/pages/haomo/test-component/hm-reply-card)

更多毫末科技的uni-app跨端模板，请见[毫末科技uni-app跨端模板](https://haomo-tech.com/sale.html)

## 技术支持

* [uni-app插件市场](https://ext.dcloud.net.cn/plugin?id=1551)

* [npm包](https://www.npmjs.com/package/hm-uniapp-reply-card)

* [github地址](https://github.com/haomo-studio/hm-uniapp-reply-card)

* [gitee地址](https://gitee.com/haomo/hm-uniapp-reply-card)

毫末科技将长期迭代本组件。需要技术支持，请进钉钉群（群号30423559）：

<img width="250" src="http://downloads.haomo-tech.com/%E6%AF%AB%E6%9C%ABuniapp%E7%BB%84%E4%BB%B6%E6%8A%80%E6%9C%AF%E6%94%AF%E6%8C%81.jpg">

## 概述

毫末uni-app毫末评论回复卡片组件。支持H5/小程序(微信、支付宝、头条、百度、QQ)/App；组件可自适应各种屏幕大小的手机。

## 使用

请使用HBuilderX导入组件。

在script中引用：

```javascript
import HmReplyCard from '@/components/hm-reply-card/index.vue'
export default {
    components: { HmReplyCard }
}
```

在template中使用：

```html
<template>
  <div class="test-component">
    <hm-reply-card :options="options"></hm-reply-card>
  </div>
</template>
<script>
import HmReplyCard from '@/components/hm-components/hm-reply-card/index.vue'

export default {
  components: { HmReplyCard },
  data() {
    return {
      options: {
          newComments: '新评论',
          dot:
            '/static/hm-reply-card/images/img_26225_0_4.png',
          dot_2:
            '/static/hm-reply-card/images/img_26225_0_5.png',
          dot_3:
            '/static/hm-reply-card/images/img_26225_0_6.png',
          shopCreditLv1:
            '/static/hm-reply-card/images/img_26225_0_3.png',
          desc: '张三已经回答了你对他的设计的评论',
          twoDaysAgo: '两天前',
          creditLv1:
            '/static/hm-reply-card/images/img_26225_0_2.png',
          desc_2: '李四回答了你对她的项目的评论…',
          num: '3',
          daysAgo: '天前',
          lanzuanLv1:
            '/static/hm-reply-card/images/img_26225_0_1.png',
          desc_3: '王五已经回答了你对他的计划的评论',
          num_2: '4',
          daysAgo_2: '天前',
          huangzuanLv1:
            '/static/hm-reply-card/images/img_26225_0_0.png',
          desc_4: '赵六已经回答了你对她的设计的评论',
          num_3: '5',
          daysAgo_3: '天前'
        }
    };
  },
  methods: {
    onClick: function(e) {
      console.log('onClick');
    }
  }
};
</script>
<style>
</style>

```

## 属性说明

| 属性名        | 类型     | 默认值 | 说明                                                                       |
|-----------   |---------|--------|----------------------------------------------------------------------------|
| options        | Object  | -      | 卡片属性                                                                   |

options对象各个属性说明如下：

| 属性名        | 类型     | 默认值 | 说明                                                                       |
|-----------   |---------|--------|----------------------------------------------------------------------------|
| newComments        | String  | -      | 标题文字                                                                   |
| dot        | String  | -      | 状态图片                                                                   |
| desc        | String  | -      | 内容                                                                   |

## 事件说明

| 事件称名   | 事件说明           | 返回参数 |
|----------|--------------------|----------|
| @click   | 点击 Card 触发事件 | -        |

## 更新日志

### 0.0.1(2020-04-01)

* 完成第一个版本
