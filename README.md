<strong>Strip Editor Artefacts Module</strong>

Remove artefacts from Drupal nodes on saving - i.e. strip out any occurences of <code>&lt;p&gt;&amp;nbsp;&lt;/p&gt;</code> that are created by CKEditor in Drupal 8.

Note that this module cannot distinguish between those created intentionally and those created unintentionally, so will remove anything that exactly matches <code>&lt;p&gt;&amp;nbsp;&lt;/p&gt;</code>. Therefore, to keep any such paragraphs, make a minor modification (such as adding a class or a second <code>&amp;nbsp;</code>).

See https://www.drupal.org/project/drupal/issues/2876094 for more details of the issue that this aims to address.
