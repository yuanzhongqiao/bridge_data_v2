<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto" class=""><a id="user-content-jax-bcrl-implementations-for-bridgedata-v2" class="anchor" aria-hidden="true" tabindex="-1" href="#jax-bcrl-implementations-for-bridgedata-v2"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BridgeData V2 的 Jax BC/RL 实现</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://rail-berkeley.github.io/bridgedata/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该存储库提供了用于BridgeData V2</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">培训的代码</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们提供了本文中描述的以下方法子集的实现：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目标条件BC</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有扩散政策的目标条件BC</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目标条件IQL</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目标条件对比强化学习</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">语言条件BC</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有方法的官方实现和论文可以在这里找到：</font></font></p>
<ul dir="auto">
<li><a href="https://github.com/philippe-eecs/IDQL"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IDQL</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（IQL + 扩散政策）[ </font></font><a href="https://github.com/philippe-eecs/IDQL"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hansen-Estruch 等人。</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">] 和</font></font><a href="https://diffusion-policy.cs.columbia.edu/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扩散政策</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[ </font></font><a href="https://diffusion-policy.cs.columbia.edu/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Chi 等人。</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]</font></font></li>
<li><a href="https://github.com/ikostrikov/implicit_q_learning"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IQL</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> [ </font></font><a href="https://arxiv.org/abs/2110.06169" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kostrikov 等人。</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]</font></font></li>
<li><a href="https://chongyi-zheng.github.io/stable_contrastive_rl/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对比强化学习</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[ </font></font><a href="https://arxiv.org/abs/2306.03346" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Zheng et al. </font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font></font><a href="https://arxiv.org/abs/2206.07568" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">艾森巴赫等人。</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]</font></font></li>
<li><a href="https://github.com/google-research/robotics_transformer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RT-1</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> [</font></font><a href="https://arxiv.org/abs/2212.06817" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">布罗汉等人。</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]</font></font></li>
<li><a href="https://github.com/tonyzhaozh/act"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ACT</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> [</font></font><a href="https://arxiv.org/abs/2304.13705" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">赵等人。</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">]</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您遇到此代码问题，请打开 GitHub 问题。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-data" class="anchor" aria-hidden="true" tabindex="-1" href="#data"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://rail.eecs.berkeley.edu/datasets/bridge_release/data/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">原始数据集（由 JPEG、PNG 和 pkl 文件组成）可以在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font><font style="vertical-align: inherit;">。</font></font><code>demos*.zip</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件包含演示数据，并</font></font><code>scripted*.zip</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包含使用脚本化策略收集的数据。</font><font style="vertical-align: inherit;">对于训练，原始数据需要转换为与数据加载器兼容的格式。</font><font style="vertical-align: inherit;">我们提供两种选择：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自定义</font></font><code>tf.data</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加载程序。</font><font style="vertical-align: inherit;">该数据加载器</font></font><code>jaxrl_m/data/bridge_dataset.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此存储库中的训练脚本中实现并由其使用。</font><font style="vertical-align: inherit;">该</font></font><code>data_processing</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件夹中的脚本将原始数据转换为该数据加载器所需的格式。</font><font style="vertical-align: inherit;">首先，用于</font></font><code>bridgedata_raw_to_numpy.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将原始数据转换为 NumPy 文件。</font><font style="vertical-align: inherit;">然后，使用</font></font><code>bridgedata_numpy_to_tfrecord.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 NumPy 文件转换为 TFRecord 文件。</font></font></li>
<li><font style="vertical-align: inherit;"></font><a href="https://www.tensorflow.org/datasets/catalog/overview" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TensorFlow 数据</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集加载</font><font style="vertical-align: inherit;">器。</font><font style="vertical-align: inherit;">Tensorflow Datasets 是一个高级包装器</font></font><code>tf.data</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><a href="https://rail.eecs.berkeley.edu/datasets/bridge_release/data/" rel="nofollow"><font style="vertical-align: inherit;">我们在此处</font></a></font><code>tfds</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的文件夹</font><font style="vertical-align: inherit;">中提供了数据集的预处理 TFDS 版本（下采样至 256x256）</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">在 TFDS 数据集中，轨迹是使用</font><a href="https://github.com/google-research/rlds"><font style="vertical-align: inherit;">RLDS</font></a><font style="vertical-align: inherit;">格式构建的。</font><font style="vertical-align: inherit;">Kevin Black 的</font><a href="https://github.com/kvablack/dlimp"><font style="vertical-align: inherit;">DLIMP</font></a><font style="vertical-align: inherit;">存储库提供了有用的工具，用于加载 RLDS 格式的 TFDS 数据集并将转换应用于该数据集（请参阅该</font><font style="vertical-align: inherit;">函数）。</font></font><a href="https://rail.eecs.berkeley.edu/datasets/bridge_release/data/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://github.com/google-research/rlds"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="https://github.com/kvablack/dlimp"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><code>from_rlds</code><font style="vertical-align: inherit;"></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-training" class="anchor" aria-hidden="true" tabindex="-1" href="#training"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">训练</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要开始训练，请运行以下命令。</font><font style="vertical-align: inherit;">替换</font></font><code>METHOD</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为</font></font><code>gc_bc</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>gc_ddpm_bc</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>gc_iql</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或之一</font></font><code>contrastive_rl_td</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并替换</font></font><code>NAME</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为运行的名称。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python experiments/train.py \
    --config experiments/configs/train_config.py:METHOD \
    --bridgedata_config experiments/configs/data_config.py:all \
    --name NAME
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python experiments/train.py \
    --config experiments/configs/train_config.py:METHOD \
    --bridgedata_config experiments/configs/data_config.py:all \
    --name NAME" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以在 中修改训练超参数，</font></font><code>experiments/configs/data_config.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并且可以在 中修改数据参数（例如要包含/排除的子集）</font></font><code>experiments/configs/train_config.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-evaluation" class="anchor" aria-hidden="true" tabindex="-1" href="#evaluation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">评估</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://docs.google.com/document/d/1si-6cTElTWTgflwcZRPfgHU7-UwfCUkEztkH3ge5CGc/edit?usp=sharing" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，根据我们的指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置机器人硬件</font><font style="vertical-align: inherit;">。</font></font><a href="https://github.com/rail-berkeley/bridge_data_robot"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从此存储库</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装我们的 WidowX 机器人控制器堆栈</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有两种方法可以将策略与机器人控制器连接：docker compose 服务方法或服务器-客户端方法。</font><font style="vertical-align: inherit;">请参阅</font></font><a href="https://github.com/rail-berkeley/bridge_data_robot"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bridge_data_robot</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档，了解如何设置每种方法的说明。</font><font style="vertical-align: inherit;">一般来说，我们推荐服务器-客户端方式。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于服务器-客户端方法，在机器人上启动服务器。</font><font style="vertical-align: inherit;">然后在客户端运行以下命令。</font><font style="vertical-align: inherit;">您可以通过该标志指定远程服务器的IP </font></font><code>--ip</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">默认IP为</font></font><code>localhost</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（即服务器和客户端是同一台机器）。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> Specify the path to the downloaded checkpoints directory</span>
<span class="pl-k">export</span> CHECKPOINT_DIR=/path/to/checkpoint_dir

<span class="pl-c"><span class="pl-c">#</span> For GCBC</span>
python experiments/eval.py \
  --checkpoint_weights_path <span class="pl-smi">$CHECKPOINT_DIR</span>/checkpoint_300000 \
  --checkpoint_config_path <span class="pl-smi">$CHECKPOINT_DIR</span>/gcbc_256_config.json \
  --im_size 256 --goal_type gc --show_image --blocking

<span class="pl-c"><span class="pl-c">#</span> For LCBC</span>
python experiments/eval.py \
  --checkpoint_weights_path <span class="pl-smi">$CHECKPOINT_DIR</span>/checkpoint_145000 \
  --checkpoint_config_path <span class="pl-smi">$CHECKPOINT_DIR</span>/lcbc_256_config.json \
  --im_size 256 --goal_type lc --show_image --blocking</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# Specify the path to the downloaded checkpoints directory
export CHECKPOINT_DIR=/path/to/checkpoint_dir

# For GCBC
python experiments/eval.py \
  --checkpoint_weights_path $CHECKPOINT_DIR/checkpoint_300000 \
  --checkpoint_config_path $CHECKPOINT_DIR/gcbc_256_config.json \
  --im_size 256 --goal_type gc --show_image --blocking

# For LCBC
python experiments/eval.py \
  --checkpoint_weights_path $CHECKPOINT_DIR/checkpoint_145000 \
  --checkpoint_config_path $CHECKPOINT_DIR/lcbc_256_config.json \
  --im_size 256 --goal_type lc --show_image --blocking" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以使用 flag 指定末端执行器的初始位置</font></font><code>--initial_eep</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">同样，在拍摄目标图像时，使用该标志</font></font><code>--goal_eep</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指定末端执行器的位置。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要使用 docker compose 服务方法评估图像条件或语言条件方法，</font><font style="vertical-align: inherit;">请分别在docker 容器中运行</font></font><code>eval_gc.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font><font style="vertical-align: inherit;">。</font></font><code>eval_lc.py</code><font style="vertical-align: inherit;"></font><code>bridge_data_v2</code><font style="vertical-align: inherit;"></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-provided-checkpoints" class="anchor" aria-hidden="true" tabindex="-1" href="#provided-checkpoints"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供的检查点</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GCBC、LCBC、D-GCBC、GCIQL 和 CRL 的检查点可</font></font><a href="https://rail.eecs.berkeley.edu/datasets/bridge_release/checkpoints/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到。</font><font style="vertical-align: inherit;">每个检查点都有一个关联的 JSON 文件及其配置信息。</font><font style="vertical-align: inherit;">每个检查点的名称表明它是使用 128x128 图像还是 256x256 图像进行训练。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们目前没有 ACT 或 RT-1 的检查点，但可能很快就会发布。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-environment" class="anchor" aria-hidden="true" tabindex="-1" href="#environment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该代码库的依赖项可以安装在 conda 环境中：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>conda create -n jaxrl python=3.10
conda activate jaxrl
pip install -e <span class="pl-c1">.</span> 
pip install -r requirements.txt</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="conda create -n jaxrl python=3.10
conda activate jaxrl
pip install -e . 
pip install -r requirements.txt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于 GPU：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install --upgrade <span class="pl-s"><span class="pl-pds">"</span>jax[cuda11_pip]==0.4.13<span class="pl-pds">"</span></span> -f https://storage.googleapis.com/jax-releases/jax_cuda_releases.html</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install --upgrade &quot;jax[cuda11_pip]==0.4.13&quot; -f https://storage.googleapis.com/jax-releases/jax_cuda_releases.html" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于TPU</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip install --upgrade "jax[tpu]==0.4.13" -f https://storage.googleapis.com/jax-releases/libtpu_releases.html
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install --upgrade &quot;jax[tpu]==0.4.13&quot; -f https://storage.googleapis.com/jax-releases/libtpu_releases.html" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关安装 Jax 的更多详细信息，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="https://github.com/google/jax"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jax Github 页面。</font></font></a><font style="vertical-align: inherit;"></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-cite" class="anchor" aria-hidden="true" tabindex="-1" href="#cite"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引用</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此代码基于Dibya Ghosh 的</font></font><a href="https://github.com/dibyaghosh/jaxrl_m"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">jaxrl_m</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您在工作中使用此代码和/或 BridgeData V2，请引用该论文：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@inproceedings{walke2023bridgedata,
  title={BridgeData V2: A Dataset for Robot Learning at Scale},
  author={Walke, Homer and Black, Kevin and Lee, Abraham and Kim, Moo Jin and Du, Max and Zheng, Chongyi and Zhao, Tony and Hansen-Estruch, Philippe and Vuong, Quan and He, Andre and Myers, Vivek and Fang, Kuan and Finn, Chelsea and Levine, Sergey},
  booktitle={Conference on Robot Learning (CoRL)},
  year={2023}
}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@inproceedings{walke2023bridgedata,
  title={BridgeData V2: A Dataset for Robot Learning at Scale},
  author={Walke, Homer and Black, Kevin and Lee, Abraham and Kim, Moo Jin and Du, Max and Zheng, Chongyi and Zhao, Tony and Hansen-Estruch, Philippe and Vuong, Quan and He, Andre and Myers, Vivek and Fang, Kuan and Finn, Chelsea and Levine, Sergey},
  booktitle={Conference on Robot Learning (CoRL)},
  year={2023}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</article></div>
