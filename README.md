# ETHAN DIGITAL LIBRARY v2.0 PROFESSIONAL

Suggested domain: https://library.ethandigitalacademy.org

## Major capabilities
- Installable PWA with offline application shell
- Local-first file library using IndexedDB
- PDF/TXT/Markdown/HTML local file support
- Full-text indexing for supported local text files (up to 2.5 MB each)
- Web, book, article, report, video, course, guide and template catalog records
- Rich metadata: author, year, publisher/source, ISBN/DOI/identifier, category, tags
- Open Library ISBN metadata lookup (public API, no secret key stored)
- Advanced field search: author:, tag:, year:, type:, status:, rating:, publisher:, isbn:
- Gallery, list and table views
- Sorting by recency, title, year, rating and progress
- Favourites, Want to Read, Reading, Completed and Recent views
- Smart collections for high ratings, missing metadata, local files and web resources
- Hierarchical custom collections
- Saved searches
- Bulk status and bulk tagging
- Reading progress, ratings and personal reviews
- Resource annotations/highlights with page/section/location field
- Research notebook
- Reading session logging and 7-day activity view
- APA/MLA/Chicago citation drafts with verification reminder
- BibTeX and RIS export per resource or whole library
- Duplicate-resource warning
- JSON backup/import of catalog, collections, notes, saved searches and sessions
- Responsive desktop/tablet/mobile UI

## Important notes
- Local uploaded file binaries stay in that device/browser's IndexedDB. JSON backup preserves metadata but does not embed local file bytes.
- PDF text extraction/annotation is not implemented in this standalone dependency-free build; annotations are stored as user-entered notes tied to each resource.
- Citation text is a convenience draft and should be checked against the institution's required style guide.
- Open Library lookup requires internet access and depends on Open Library availability.
- A cloud backend such as Supabase can later add account sync, instructor-published resources, shared libraries, file storage, permissions and cross-device access.
