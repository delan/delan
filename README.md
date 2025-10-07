<!--
  accepted: @width @align p br table tr td q sup sub h1 h2 h3 h4 h5 h6 samp kbd
  rejected: @style @class @data colgroup col font small big dfn center svg
  useless: table@width table@border table@frame table@rules

  h3: 1.25em bold bottom16px top24px
  h4: 1em bold bottom16px top24px
  p: 1em bottom16px

  use sup/sub as small or to fine-tine spacing (can be nested)
-->

<table>
  <tr>
    <!--
      stylesheet has table{width:max-content;max-width:100%}
      so use td@width=9999999 over table@width=100%
    -->
    <td bgcolor="blue" colspan="2" width="9999999" align="center">
      <h1><samp>
        <a href="https://shuppy.org">~</a>
        : <a href="https://www.azabani.com/about/">~/work/</a>
        : <a href="https://www.azabani.com/labs/">~/labs/</a>
        : <a href="https://bitbucket.org/delan">bitbucket</a>
        : <a href="https://codeberg.org/shuppy">codeberg</a>
      </samp></h1>
  <tr>
    <td width="50%">
      <b><a href="https://bitbucket.org/delan/matrix86">matrix86</a></b><br>
      <sub>cmatrix clone in three eighths of a PC MBR<br>x86 (nasm)</sub>
    <td width="50%">
      <b><a href="https://bitbucket.org/delan/xd">xd</a></b><br>
      <sub>dumps binary input in a variety of formats<br>Rust</sub>
  <tr>
    <td width="50%">
      <b><a href="https://bitbucket.org/delan/badapple.rs">badapple.rs</a></b><br>
      <sub>Bad Apple!! for taskmgr<br>Rust</sub>
    <td width="50%">
      <b><a href="https://bitbucket.org/delan/ing2ynab">ing2ynab</a></b><br>
      <sub>cleans up ing.com.au transactions for YNAB<br>Rust</sub>
  <tr>
    <td width="50%">
      <b><a href="https://bitbucket.org/delan/nonymous">nonymous</a></b><br>
      <sub>DNS library (no-{std,alloc}-friendly) and tools<br>Rust</sub>
    <td width="50%">
      <b><a href="https://codeberg.org/shuppy/fallen-sky">fallen-sky</a></b><br>
      <sub>tools for <a href="https://github.com/falling-sky">falling-sky</a>, the IPv6 diagnostic service that powers <a href="https://test-ipv6.com">test-ipv6.com</a> and <a href="https://sixte.st">sixte.st</a>.<br>Rust</sub>
</table>
