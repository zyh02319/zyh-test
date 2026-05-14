<template>
  <header class="site-header">
    <div class="brand">Maple Table</div>
    <nav class="site-nav" aria-label="主导航">
      <a href="#menu">菜单</a>
      <a href="#story">故事</a>
      <a href="#visit">到店</a>
      <a href="#reviews">评价</a>
    </nav>
    <a class="header-cta" href="#reserve">立即订位</a>
  </header>

  <main>
    <section class="hero" id="reserve">
      <div class="hero-media">
        <img
          src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&w=1600&q=80"
          alt="暖色灯光下的现代餐厅用餐空间"
        >
      </div>
      <div class="hero-copy">
        <p class="eyebrow">A Table Lit By The Seasons</p>
        <h1>把风味、火候与夜色，安静地端上桌。</h1>
        <p class="hero-text">
          时令在厨房里缓慢生长，炉火把香气一点点推向门外。我们想做的，不过是一张能让人放下匆忙，
          把夜晚认真吃完的餐桌。
        </p>
        <div class="hero-actions">
          <a class="button button-primary" href="#visit">查看营业时间</a>
          <a class="button button-secondary" href="#menu">本周推荐</a>
        </div>
        <div class="booking-card">
          <div>
            <p class="booking-label">今日可订</p>
            <p class="booking-value">18:30 / 20:15</p>
          </div>
          <div>
            <p class="booking-label">联系电话</p>
            <p class="booking-value">021-6688-1024</p>
          </div>
          <div>
            <p class="booking-label">地址</p>
            <p class="booking-value">静安区铜仁路 88 号</p>
          </div>
        </div>
      </div>
    </section>

    <section class="highlights">
      <article>
        <span>01</span>
        <h2>开放式厨房</h2>
        <p>从炉火到摆盘都能看见，节奏感是这间店里的一部分。</p>
      </article>
      <article>
        <span>02</span>
        <h2>季节菜单</h2>
        <p>每六周更新一次，围绕当季食材做小幅度但明确的变化。</p>
      </article>
      <article>
        <span>03</span>
        <h2>自然酒与特调</h2>
        <p>酒单偏轻盈清爽，也准备了适合不喝酒客人的风味饮品。</p>
      </article>
    </section>

    <section class="menu-section" id="menu">
      <div class="section-heading">
        <p class="eyebrow">Chef Picks</p>
        <h2>本周招牌</h2>
      </div>
      <div class="menu-grid">
        <article class="menu-card featured">
          <img
            src="https://images.unsplash.com/photo-1544025162-d76694265947?auto=format&fit=crop&w=900&q=80"
            alt="摆盘精致的炭烤牛排与蔬菜"
          >
          <div class="menu-copy">
            <div class="menu-title-row">
              <h3>炭烤肋眼配黑蒜黄油</h3>
              <span>198</span>
            </div>
            <p>28 天熟成肋眼、焦糖洋葱泥、炭烤芦笋。</p>
          </div>
        </article>
        <article class="menu-card">
          <div class="menu-copy">
            <div class="menu-title-row">
              <h3>海盐奶油卷</h3>
              <span>32</span>
            </div>
            <p>每日现烤，配发酵海藻黄油。</p>
          </div>
        </article>
        <article class="menu-card">
          <div class="menu-copy">
            <div class="menu-title-row">
              <h3>南瓜烩饭</h3>
              <span>88</span>
            </div>
            <p>烤南瓜、鼠尾草脆片、帕玛森泡沫。</p>
          </div>
        </article>
        <article class="menu-card">
          <div class="menu-copy">
            <div class="menu-title-row">
              <h3>柚香甘鲷</h3>
              <span>136</span>
            </div>
            <p>低温慢煎鱼排、白味噌酱汁、时蔬沙拉。</p>
          </div>
        </article>
        <article class="menu-card">
          <div class="menu-copy">
            <div class="menu-title-row">
              <h3>无花果巴斯克</h3>
              <span>46</span>
            </div>
            <p>轻焦香芝士体，搭配鲜无花果与蜂蜜。</p>
          </div>
        </article>
      </div>
    </section>

    <section class="story-section" id="story">
      <div class="story-copy">
        <p class="eyebrow">Our Story</p>
        <h2>一间为“想认真吃饭的人”准备的餐厅。</h2>
        <p>
          Maple Table 从一张四人木桌开始。我们喜欢烟火气，也喜欢精确；喜欢舒适，
          也在意每道菜最后一口的层次。这间店想给人的感觉不是“正式”，而是被认真对待。
        </p>
        <a class="text-link" href="#visit">了解到店体验</a>
      </div>
      <div class="story-media">
        <img
          src="https://images.unsplash.com/photo-1559339352-11d035aa65de?auto=format&fit=crop&w=1200&q=80"
          alt="厨师在开放式厨房处理食材"
        >
      </div>
    </section>

    <section class="visit-section" id="visit">
      <div class="section-heading">
        <p class="eyebrow">Visit Us</p>
        <h2>来店信息</h2>
      </div>
      <div class="visit-layout">
        <div class="visit-panel">
          <h3>营业时间</h3>
          <ul>
            <li><span>周一至周五</span><strong>11:30 - 14:00 / 17:30 - 22:00</strong></li>
            <li><span>周六</span><strong>10:30 - 22:30</strong></li>
            <li><span>周日</span><strong>10:30 - 21:30</strong></li>
          </ul>
        </div>
        <div class="visit-panel">
          <h3>用餐提示</h3>
          <ul>
            <li><span>座位安排</span><strong>吧台、双人桌与 6 人长桌</strong></li>
            <li><span>预约建议</span><strong>晚市提前 1 至 2 天</strong></li>
            <li><span>停车信息</span><strong>商场地下停车场可直达</strong></li>
          </ul>
        </div>
      </div>
    </section>

    <section class="reviews-section" id="reviews">
      <div class="section-heading">
        <p class="eyebrow">Guest Notes</p>
        <h2>客人怎么说</h2>
      </div>
      <div class="reviews-grid">
        <blockquote>
          “环境松弛但不随便，服务很稳，牛排火候尤其好。”
          <cite>Lin，常客</cite>
        </blockquote>
        <blockquote>
          “早午餐的节奏很好，适合慢慢坐着聊天，甜品值得留肚子。”
          <cite>Qiao，周末来访</cite>
        </blockquote>
        <blockquote>
          “不是那种浮夸餐厅，细节却很到位，适合带朋友来见面。”
          <cite>Ming，首次到店</cite>
        </blockquote>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div>
      <div class="brand">Maple Table</div>
      <p>城市餐叙，认真吃饭。</p>
    </div>
    <a class="header-cta" href="tel:02166881024">电话订位</a>
  </footer>
</template>
