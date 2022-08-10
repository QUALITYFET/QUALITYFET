- 👋 Hi, I’m @QUALITYFET
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

## ➡️ Available options

<!--options-->
<table>
  <tr>
    <td align="center" nowrap="nowrap">Option</i></td><td align="center" nowrap="nowrap">Description</td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_reactions</code></h4></td>
    <td rowspan="2"><p>Enable reactions plugin</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>boolean</code>
<br>
<b>default:</b> no<br></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_reactions_limit</code></h4></td>
    <td rowspan="2"><p>Display limit (issues and pull requests comments)</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>number</code>
<i>(0 ≤
𝑥
≤ 1000)</i>
<br>
<b>default:</b> 200<br></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_reactions_limit_issues</code></h4></td>
    <td rowspan="2"><p>Display limit (issues and pull requests, first comment)</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>number</code>
<i>(0 ≤
𝑥
≤ 1000)</i>
<br>
<b>default:</b> 100<br></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_reactions_limit_discussions</code></h4></td>
    <td rowspan="2"><p>Display limit (discussions, first comment)</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>number</code>
<i>(0 ≤
𝑥
≤ 1000)</i>
<br>
<b>default:</b> 100<br></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_reactions_limit_discussions_comments</code></h4></td>
    <td rowspan="2"><p>Display limit (discussions comments)</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>number</code>
<i>(0 ≤
𝑥
≤ 1000)</i>
<br>
<b>default:</b> 100<br></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_reactions_days</code></h4></td>
    <td rowspan="2"><p>Comments maximum age</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>number</code>
<i>(0 ≤
𝑥)</i>
<br>
<b>zero behaviour:</b> disable</br>
<b>default:</b> 0<br></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_reactions_display</code></h4></td>
    <td rowspan="2"><p>Display mode</p>
<ul>
<li><code>absolute</code>: scale percentages using total reactions count</li>
<li><code>relative</code>: scale percentages using highest reaction count</li>
</ul>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>string</code>
<br>
<b>default:</b> absolute<br>
<b>allowed values:</b><ul><li>absolute</li><li>relative</li></ul></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_reactions_details</code></h4></td>
    <td rowspan="2"><p>Additional details</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>array</code>
<i>(comma-separated)</i>
<br>
<b>allowed values:</b><ul><li>count</li><li>percentage</li></ul></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_reactions_ignored</code></h4></td>
    <td rowspan="2"><p>Ignored users</p>
<p>Can be used to ignore bots activity</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap">⏩ Inherits <code>users_ignored</code><br>
<b>type:</b> <code>array</code>
<i>(comma-separated)</i>
<br></td>
  </tr>
</table>
<!--/options-->

## ℹ️ Examples workflows

<!--examples-->
```yaml
name: Comment reactions
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.reactions.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ""
  plugin_reactions: yes
  plugin_reactions_limit: 100
  plugin_reactions_details: percentage
  
--------------------------------------------------------------------------------------------------------------------

    <foreignObject x="0" y="0" width="100%" height="100%">
        <div xmlns="http://www.w3.org/1999/xhtml" xmlns:xlink="http://www.w3.org/1999/xlink" class="items-wrapper">
            <section>
                <h2 class="field">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                        <path fill-rule="evenodd" d="M1.75 2.5a.75.75 0 000 1.5h6.5a.75.75 0 000-1.5h-6.5zm4 5a.75.75 0 000 1.5h7.5a.75.75 0 000-1.5h-7.5zm0 5a.75.75 0 000 1.5h7.5a.75.75 0 000-1.5h-7.5zM3 8a1 1 0 11-2 0 1 1 0 012 0zm-1 6a1 1 0 100-2 1 1 0 000 2z"/>
                        <path d="M13.314 4.918L11.07 2.417A.25.25 0 0111.256 2h4.488a.25.25 0 01.186.417l-2.244 2.5a.25.25 0 01-.372 0z"/>
                    </svg>
                    7 Star lists
                </h2>
                <div class="row">
                    <section>
                        <div class="starlist">
                            <h2 class="field">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                    <path fill-rule="evenodd" d="M2 4a1 1 0 100-2 1 1 0 000 2zm3.75-1.5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zm0 5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zm0 5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zM3 8a1 1 0 11-2 0 1 1 0 012 0zm-1 6a1 1 0 100-2 1 1 0 000 2z"/>
                                </svg>
                                Awesome
                            </h2>
                            <div class="count">26 repositories</div>
                            <div class="description">Thanks for contributing to mankind progress !</div>
                            <div class="languages">
                                <div class="row">
                                    <svg class="bar" xmlns="http://www.w3.org/2000/svg" width="420" height="8">
                                        <mask id="languages-bar">
                                            <rect x="0" y="0" width="420" height="8" fill="white" rx="5"/>
                                        </mask>
                                        <rect mask="url(#languages-bar)" x="0" y="0" width="0" height="8" fill="#d1d5da"/>
                                        <rect mask="url(#languages-bar)" x="0" y="0" width="122.50000000000001" height="8" fill="#3178c6"/>
                                        <rect mask="url(#languages-bar)" x="122.50000000000001" y="0" width="122.50000000000001" height="8" fill="#f1e05a"/>
                                        <rect mask="url(#languages-bar)" x="245.00000000000003" y="0" width="52.5" height="8" fill="#f34b7d"/>
                                        <rect mask="url(#languages-bar)" x="297.5" y="0" width="52.5" height="8" fill="#555555"/>
                                        <rect mask="url(#languages-bar)" x="350" y="0" width="17.5" height="8" fill="#dea584"/>
                                        <rect mask="url(#languages-bar)" x="367.5" y="0" width="17.5" height="8" fill="#140f46"/>
                                        <rect mask="url(#languages-bar)" x="385" y="0" width="17.5" height="8" fill="#701516"/>
                                        <rect mask="url(#languages-bar)" x="402.49999999999994" y="0" width="17.5" height="8" fill="#b07219"/>
                                    </svg>
                                </div>
                                <div class="row">
                                    <section>
                                        <div class="field language details">
                                            <div class="field">
                                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                                    <path fill="#3178c6" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/>
                                                </svg>
                                                TypeScript
                                            </div>
                                            <small>
                                                <div>26.92%</div>
                                                <div>7★</div>
                                            </small>
                                        </div>
                                        <div class="field language details">
                                            <div class="field">
                                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                                    <path fill="#f34b7d" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/>
                                                </svg>
                                                C++
                                            </div>
                                            <small>
                                                <div>11.54%</div>
                                                <div>3★</div>
                                            </small>
                                        </div>
                                        <div class="field language details">
                                            <div class="field">
                                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                                    <path fill="#dea584" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/>
                                                </svg>
                                                Rust
                                            </div>
                                            <small>
                                                <div>3.85%</div>
                                                <div>1★</div>
                                            </small>
                                        </div>
                                        <div class="field language details">
                                            <div class="field">
                                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                                    <path fill="#701516" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/>
                                                </svg>
                                                Ruby
                                            </div>
                                            <small>
                                                <div>3.85%</div>
                                                <div>1★</div>
                                            </small>
                                        </div>
                                    </section>
                                    <section>
                                        <div class="field language details">
                                            <div class="field">
                                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                                    <path fill="#f1e05a" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/>
                                                </svg>
                                                JavaScript
                                            </div>
                                            <small>
                                                <div>26.92%</div>
                                                <div>7★</div>
                                            </small>
                                        </div>
                                        <div class="field language details">
                                            <div class="field">
                                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                                    <path fill="#555555" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/>
                                                </svg>
                                                C
                                            </div>
                                            <small>
                                                <div>11.54%</div>
                                                <div>3★</div>
                                            </small>
                                        </div>
                                        <div class="field language details">
                                            <div class="field">
                                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                                    <path fill="#140f46" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/>
                                                </svg>
                                                CodeQL
                                            </div>
                                            <small>
                                                <div>3.85%</div>
                                                <div>1★</div>
                                            </small>
                                        </div>
                                        <div class="field language details">
                                            <div class="field">
                                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                                    <path fill="#b07219" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/>
                                                </svg>
                                                Java
                                            </div>
                                            <small>
                                                <div>3.85%</div>
                                                <div>1★</div>
                                            </small>
                                        </div>
                                    </section>
                                </div>
                            </div>
                            <div class="repositories">
                            </div>
                        </div>
                    </section>
                </div>
            </section>
        </div>
        <div xmlns="http://www.w3.org/1999/xhtml" id="metrics-end"></div>
    </foreignObject>
</svg>
