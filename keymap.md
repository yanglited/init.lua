# Grepped be grep -r -A5 "vim.keymap.set" ~/.config/nvim
```
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<leader>pv", vim.cmd.Ex)
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("v", "J", ":m '>+1<CR>gv=gv")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("v", "K", ":m '<-2<CR>gv=gv")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "J", "mzJ`z")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<C-d>", "<C-d>zz")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<C-u>", "<C-u>zz")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "n", "nzzzv")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "N", "Nzzzv")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<leader>vwm", function()
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-    require("vim-with-me").StartVimWithMe()
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-end)
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<leader>svwm", function()
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-    require("vim-with-me").StopVimWithMe()
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-end)
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-
/home/yli/.config/nvim/lua/theprimeagen/remap.lua--- greatest remap ever
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("x", "<leader>p", [["_dP]])
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-
/home/yli/.config/nvim/lua/theprimeagen/remap.lua--- next greatest remap ever : asbjornHaland
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set({"n", "v"}, "<leader>y", [["+y]])
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<leader>Y", [["+Y]])
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set({"n", "v"}, "<leader>d", [["_d]])
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-
/home/yli/.config/nvim/lua/theprimeagen/remap.lua--- This is going to get me cancelled
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("i", "<C-c>", "<Esc>")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "Q", "<nop>")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<C-f>", "<cmd>silent !tmux neww tmux-sessionizer<CR>")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<leader>f", vim.lsp.buf.format)
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<C-k>", "<cmd>cnext<CR>zz")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<C-j>", "<cmd>cprev<CR>zz")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<leader>k", "<cmd>lnext<CR>zz")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<leader>j", "<cmd>lprev<CR>zz")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<leader>s", [[:%s/\<<C-r><C-w>\>/<C-r><C-w>/gI<Left><Left><Left>]])
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<leader>x", "<cmd>!chmod +x %<CR>", { silent = true })
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<leader>vpp", "<cmd>e ~/.dotfiles/nvim/.config/nvim/lua/theprimeagen/packer.lua<CR>");
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<leader>mr", "<cmd>CellularAutomaton make_it_rain<CR>");
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-
/home/yli/.config/nvim/lua/theprimeagen/remap.lua:vim.keymap.set("n", "<leader><leader>", function()
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-    vim.cmd("so")
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-end)
/home/yli/.config/nvim/lua/theprimeagen/remap.lua-
--
/home/yli/.config/nvim/after/plugin/trouble.lua:vim.keymap.set("n", "<leader>xq", "<cmd>TroubleToggle quickfix<cr>",
/home/yli/.config/nvim/after/plugin/trouble.lua-  {silent = true, noremap = true}
/home/yli/.config/nvim/after/plugin/trouble.lua-)
--
/home/yli/.config/nvim/after/plugin/telescope.lua:vim.keymap.set('n', '<leader>pf', builtin.find_files, {})
/home/yli/.config/nvim/after/plugin/telescope.lua:vim.keymap.set('n', '<C-p>', builtin.git_files, {})
/home/yli/.config/nvim/after/plugin/telescope.lua:vim.keymap.set('n', '<leader>ps', function()
/home/yli/.config/nvim/after/plugin/telescope.lua-	builtin.grep_string({ search = vim.fn.input("Grep > ") })
/home/yli/.config/nvim/after/plugin/telescope.lua-end)
/home/yli/.config/nvim/after/plugin/telescope.lua:vim.keymap.set('n', '<leader>vh', builtin.help_tags, {})
/home/yli/.config/nvim/after/plugin/telescope.lua-
--
/home/yli/.config/nvim/after/plugin/harpoon.lua:vim.keymap.set("n", "<leader>a", mark.add_file)
/home/yli/.config/nvim/after/plugin/harpoon.lua:vim.keymap.set("n", "<C-e>", ui.toggle_quick_menu)
/home/yli/.config/nvim/after/plugin/harpoon.lua-
/home/yli/.config/nvim/after/plugin/harpoon.lua:vim.keymap.set("n", "<C-h>", function() ui.nav_file(1) end)
/home/yli/.config/nvim/after/plugin/harpoon.lua:vim.keymap.set("n", "<C-t>", function() ui.nav_file(2) end)
/home/yli/.config/nvim/after/plugin/harpoon.lua:vim.keymap.set("n", "<C-n>", function() ui.nav_file(3) end)
/home/yli/.config/nvim/after/plugin/harpoon.lua:vim.keymap.set("n", "<C-s>", function() ui.nav_file(4) end)
/home/yli/.config/nvim/after/plugin/harpoon.lua-
/home/yli/.config/nvim/after/plugin/harpoon.lua-
--
/home/yli/.config/nvim/after/plugin/fugitive.lua:vim.keymap.set("n", "<leader>gs", vim.cmd.Git)
/home/yli/.config/nvim/after/plugin/fugitive.lua-
/home/yli/.config/nvim/after/plugin/fugitive.lua-local ThePrimeagen_Fugitive = vim.api.nvim_create_augroup("ThePrimeagen_Fugitive", {})
/home/yli/.config/nvim/after/plugin/fugitive.lua-
/home/yli/.config/nvim/after/plugin/fugitive.lua-local autocmd = vim.api.nvim_create_autocmd
/home/yli/.config/nvim/after/plugin/fugitive.lua-autocmd("BufWinEnter", {
--
/home/yli/.config/nvim/after/plugin/fugitive.lua:        vim.keymap.set("n", "<leader>p", function()
/home/yli/.config/nvim/after/plugin/fugitive.lua-            vim.cmd.Git('push')
/home/yli/.config/nvim/after/plugin/fugitive.lua-        end, opts)
/home/yli/.config/nvim/after/plugin/fugitive.lua-
/home/yli/.config/nvim/after/plugin/fugitive.lua-        -- rebase always
/home/yli/.config/nvim/after/plugin/fugitive.lua:        vim.keymap.set("n", "<leader>P", function()
/home/yli/.config/nvim/after/plugin/fugitive.lua-            vim.cmd.Git({'pull',  '--rebase'})
/home/yli/.config/nvim/after/plugin/fugitive.lua-        end, opts)
/home/yli/.config/nvim/after/plugin/fugitive.lua-
/home/yli/.config/nvim/after/plugin/fugitive.lua-        -- NOTE: It allows me to easily set the branch i am pushing and any tracking
/home/yli/.config/nvim/after/plugin/fugitive.lua-        -- needed if i did not set the branch up correctly
/home/yli/.config/nvim/after/plugin/fugitive.lua:        vim.keymap.set("n", "<leader>t", ":Git push -u origin ", opts);
/home/yli/.config/nvim/after/plugin/fugitive.lua-    end,
/home/yli/.config/nvim/after/plugin/fugitive.lua-})
--
/home/yli/.config/nvim/after/plugin/undotree.lua:vim.keymap.set("n", "<leader>u", vim.cmd.UndotreeToggle)
/home/yli/.config/nvim/after/plugin/undotree.lua-
--
/home/yli/.config/nvim/after/plugin/lsp.lua:  vim.keymap.set("n", "gd", function() vim.lsp.buf.definition() end, opts)
/home/yli/.config/nvim/after/plugin/lsp.lua:  vim.keymap.set("n", "K", function() vim.lsp.buf.hover() end, opts)
/home/yli/.config/nvim/after/plugin/lsp.lua:  vim.keymap.set("n", "<leader>vws", function() vim.lsp.buf.workspace_symbol() end, opts)
/home/yli/.config/nvim/after/plugin/lsp.lua:  vim.keymap.set("n", "<leader>vd", function() vim.diagnostic.open_float() end, opts)
/home/yli/.config/nvim/after/plugin/lsp.lua:  vim.keymap.set("n", "[d", function() vim.diagnostic.goto_next() end, opts)
/home/yli/.config/nvim/after/plugin/lsp.lua:  vim.keymap.set("n", "]d", function() vim.diagnostic.goto_prev() end, opts)
/home/yli/.config/nvim/after/plugin/lsp.lua:  vim.keymap.set("n", "<leader>vca", function() vim.lsp.buf.code_action() end, opts)
/home/yli/.config/nvim/after/plugin/lsp.lua:  vim.keymap.set("n", "<leader>vrr", function() vim.lsp.buf.references() end, opts)
/home/yli/.config/nvim/after/plugin/lsp.lua:  vim.keymap.set("n", "<leader>vrn", function() vim.lsp.buf.rename() end, opts)
/home/yli/.config/nvim/after/plugin/lsp.lua:  vim.keymap.set("i", "<C-h>", function() vim.lsp.buf.signature_help() end, opts)
/home/yli/.config/nvim/after/plugin/lsp.lua-end)
/home/yli/.config/nvim/after/plugin/lsp.lua-
/home/yli/.config/nvim/after/plugin/lsp.lua-lsp.setup()
/home/yli/.config/nvim/after/plugin/lsp.lua-
/home/yli/.config/nvim/after/plugin/lsp.lua-vim.diagnostic.config({
--
/home/yli/.config/nvim/after/plugin/zenmode.lua:vim.keymap.set("n", "<leader>zz", function()
/home/yli/.config/nvim/after/plugin/zenmode.lua-    require("zen-mode").setup {
/home/yli/.config/nvim/after/plugin/zenmode.lua-        window = {
/home/yli/.config/nvim/after/plugin/zenmode.lua-            width = 90,
/home/yli/.config/nvim/after/plugin/zenmode.lua-            options = { }
/home/yli/.config/nvim/after/plugin/zenmode.lua-        },
--
/home/yli/.config/nvim/after/plugin/zenmode.lua:vim.keymap.set("n", "<leader>zZ", function()
/home/yli/.config/nvim/after/plugin/zenmode.lua-    require("zen-mode").setup {
/home/yli/.config/nvim/after/plugin/zenmode.lua-        window = {
/home/yli/.config/nvim/after/plugin/zenmode.lua-            width = 80,
/home/yli/.config/nvim/after/plugin/zenmode.lua-            options = { }
/home/yli/.config/nvim/after/plugin/zenmode.lua-        },
```

