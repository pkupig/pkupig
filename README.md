# <div align="center">pkupig</div>

<div align="center">
  <img src="./assets/profile-banner.svg" alt="pkupig banner" width="100%" />
</div>

<div align="center">

`Computational Geometry` `Graphics Systems` `Neural Rendering` `Interactive Tools`

</div>

## About

我主要做几何驱动的图形学、可解释的视觉表示，以及能真正落地的交互系统。

我更关心这类问题：

- 几何结构能不能直接决定表示与优化方式
- 一个方法除了“能跑”，能不能讲清楚为什么成立
- 图形算法能不能做成可演示、可交互、可复用的工具

## Featured Projects

<table>
  <tr>
    <td width="52%" valign="top">
      <h3>D · Mobius Conformal 360</h3>
      <p><strong>关键词：</strong> Möbius 变换 / 保形几何 / 360 内容 / viewport allocation</p>
      <p>这个项目把保形几何真正落到 360° 内容分配问题上：通过 Möbius warp，把采样和码率预算集中到预测视口附近，同时尽量保留关键区域的局部角度结构。</p>
      <p>我比较看重它的一点，是它不是只做视觉 demo，而是继续往 codec、trace replay、QoE 和 offline streaming proxy 的方向推进，把几何方法放进系统评价语境里。</p>
      <p>
        <a href="./D-Conformal-360/README.md">README</a> ·
        <a href="./D-Conformal-360/docs/PAPER_CORE_CONTRIBUTION.md">Core Contribution</a> ·
        <a href="./D-Conformal-360/web/index.html">Interactive Demo</a>
      </p>
    </td>
    <td width="48%" valign="top">
      <img src="./D-Conformal-360/results/compare_warps.png" alt="Mobius conformal 360 comparison" width="100%" />
      <br />
      <img src="./D-Conformal-360/web/assets/breakeven.png" alt="Mobius conformal 360 breakeven" width="100%" />
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="44%" valign="top">
      <img src="./assets/manifold-gs-card.svg" alt="Manifold GS concept card" width="100%" />
    </td>
    <td width="56%" valign="top">
      <h3>E · Manifold-Conservative Gaussian Splatting</h3>
      <p><strong>关键词：</strong> 3DGS / surface-aware representation / manifold projection / assetization</p>
      <p>我不把 3D Gaussian Splatting 里的高斯只看成“自由漂浮的辐射粒子”，而是尝试把它们解释成由流形诱导的离散几何测度。</p>
      <p>这条线更关心的问题是：一组 splats 什么时候才真正像一个可编辑、可诊断、可导出资产的几何对象，而不是只是渲染结果看起来还不错。</p>
      <p>
        <a href="./E-Manifold-GS/README.md">README</a> ·
        <a href="./E-Manifold-GS/FRAMEWORK_ZH.md">Framework ZH</a> ·
        <a href="./E-Manifold-GS/IMPLEMENTATION.md">Implementation</a>
      </p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="54%" valign="top">
      <h3>para_and_defo</h3>
      <p><strong>关键词：</strong> parameterization / mesh deformation / browser interaction / teaching demo</p>
      <p>一个我很喜欢的小而完整的项目：把三角网格参数化和变形做成浏览器里的交互式 demo，兼顾教学展示和研究原型。</p>
      <p>它提供了 ARAP、ASAP、LSCM、MVC 等参数化方法，也支持 ARAP / Laplacian deformation，并且把 3D 网格视图和 2D 参数域视图联动起来。</p>
      <p>
        <a href="./para_and_defo/defor_param/README.md">README</a>
      </p>
    </td>
    <td width="46%" valign="top">
      <img src="./para_and_defo/defor_param/checkerboard.png" alt="para and defo checkerboard" width="100%" />
    </td>
  </tr>
</table>

## More Work

除了这个仓库里的项目，我也在持续做一些方向不同、但都偏“结构明确”的系统：

- `4d`：物理驱动的 4D 稀疏占据未来预测，重点是 dynamic prediction 和 metric-calibrated serialization
- `U-spark`：结合规则系统、语义画像和微调大模型的匹配算法设计
- `claude_workshop`：围绕生成、编辑和结构化 metadata 的实验型工作区

## Working Style

```text
start from structure
  -> build a representation that can be explained
  -> connect it to an evaluation loop
  -> keep the claims honest
```

## Links

- Zhihu: https://www.zhihu.com/people/79-22-17-52-47
- GitHub: https://github.com/pkupig

## Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pkupig&show_icons=true&hide_border=true&title_color=c2410c&icon_color=c2410c&text_color=334155&bg_color=00000000" alt="pkupig github stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pkupig&layout=compact&hide_border=true&title_color=0f766e&text_color=334155&bg_color=00000000" alt="pkupig top languages" height="165" />
</div>
