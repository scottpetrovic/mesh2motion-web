# Mesh2Motion Website

<table>
  <tr>
    <td><h4>Discord<h4></td>
    <td><a href="https://discord.com/channels/1408921718231273613/1452129660791165001">Join the Discord channel</a></td>
    <td>
      <img src="https://img.shields.io/discord/1408921718231273613?label=People&color=purple" alt="Discord">
    </td>
  </tr>
</table>

Marketing website for Mesh2Motion app. The goal is to have something more information and instructional than just dumping people in the application. The goal is to potentially help people understand what the project is about and with a small potential of outside contributors improving it.

## Technology
Just a simple HTML website. No frameworks or any of that jazz. Just open the HTML page in a web browser.

## Hosting
The hosting is done via Cloudflare pages. The Github project is tied to a Cloudflare build agent. The wrangler.jsonrc file in the root directory helps the Cloudflare CI builder to deploye the content to the web. Any change to master will kick off a new build and update mesh2motion.org


## TODO
1. Bring in the mesh2model application repository
2. Hook up the application and marketing site with navigation
3. Create a small youtube video with instructions on how to use this
4. Think through marketing webpage a bit more with what needs to be included (maybe screenshot?)
5. Share with people and collect feedback on what to improve next