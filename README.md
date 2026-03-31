# Hey, I'm zLuckKing 🍀

Open source contributor focused on Android apps and manga reader tooling.

---

## 🔨 Projects

### TachiyomiSY — "For You" Recommendations Tab
> [PR #1582](https://github.com/jobobby04/TachiyomiSY/pull/1582) · Open

Added a **"For You"** tab to the main navigation bar of TachiyomiSY.  
The tab analyzes the user's entire library and suggests new manga using a cross-reference scoring system — if a title appears as a recommendation for 6 manga in your library, it gets a **+6 score**.

**Sources:** AniList · MyAnimeList · MangaUpdates · Kitsu · Shikimori · Bangumi  
**Highlights:**
- Library-aware filtering (favorited manga are automatically excluded)
- Real-time updates when manga is added to favorites
- Pull-to-refresh with smart loading states

---

### keiyoushi/extensions-source — MangaLivre Fix
> [PR #14323](https://github.com/keiyoushi/extensions-source/pull/14323) · Merged ✅

Fixed the MangaLivre extension by switching from POST to GET requests on the browse endpoint.  
Cloudflare was blocking POST requests to `/wp-admin/admin-ajax.php` for Brazilian IPs — changing the load strategy resolved the issue.

---

## 📫 Contact

GitHub issues and PRs are the best way to reach me.
