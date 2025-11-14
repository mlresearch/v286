# Paper Edit Request

## Your Role
<!-- Please mark the appropriate option with an "x" -->
- [x] I am an author of this paper
- [ ] I am acting on behalf of an author
- [ ] I am an editor of this volume
- [ ] I am acting on behalf of an editor
- [ ] Other (please describe):

If you are acting on behalf of someone, please provide their name, affiliation and Github ID:
<!-- Please provide details here -->

## Nature of Changes
<!-- Please mark the appropriate option with an "x" -->
- [ ] Minor edit to meta information (typo, formatting, etc.)
- [x] PDF change (requires proceedings editor permission)
- [ ] Content change (requires proceedings editor permission)

## For Content Changes
If this is a content change, please provide:
1. Name of the proceedings editor who gave permission:
2. Method of permission (email, verbal, etc.):
3. Date permission was granted:
4. Any relevant correspondence or notes:

## GitHub Information
Proceedings editor's GitHub username: @
<!-- This will be used to tag them in the PR -->

## Description of Changes
<!-- Please provide a detailed description of the changes you are proposing -->
1. While preparing to release our codebase, we discovered a minor issue that led to small changes in some of our reported results, specifically in the implementation of the baseline methods. 
Our method involves directly optimizing explanations for a desired property. To make a fair comparison, both our method and the baselines must be optimized using the same set of properties. However, in Figure 2 (which shows the trade-off between faithfulness and robustness for different functions), we mistakenly used a kernelized version of robustness for our method, while the baselines were evaluated using robustness defined without the kernel. In this revision, we corrected the issue by applying the robustness measure with the kernel consistently across all methods. We would like to stress that this correction does not alter the overall findings or conclusions of the paper. 
2. Proof of Proposition 1 in Appendix B had a mistake, which we have corrected. The statement of Proposition 1 is unchanged in the main text and it still holds true.

## Additional Notes
<!-- Add any other relevant information here --> 
I have recived a permission to update the PDF from the program chair(Sara Magliacane) via Email. 