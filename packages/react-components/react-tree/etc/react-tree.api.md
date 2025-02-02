## API Report File for "@fluentui/react-tree"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import type { ARIAButtonElement } from '@fluentui/react-aria';
import type { ARIAButtonSlotProps } from '@fluentui/react-aria';
import type { ComponentProps } from '@fluentui/react-utilities';
import type { ComponentState } from '@fluentui/react-utilities';
import { ContextSelector } from '@fluentui/react-context-selector';
import { FC } from 'react';
import type { ForwardRefComponent } from '@fluentui/react-utilities';
import { Provider } from 'react';
import { ProviderProps } from 'react';
import * as React_2 from 'react';
import type { Slot } from '@fluentui/react-utilities';
import type { SlotClassNames } from '@fluentui/react-utilities';

// @public (undocumented)
export const renderTree_unstable: (state: TreeState, contextValues: TreeContextValues) => JSX.Element;

// @public
export const renderTreeItem_unstable: (state: TreeItemState) => JSX.Element;

// @public
export const renderTreeItemLayout_unstable: (state: TreeItemLayoutState) => JSX.Element;

// @public
export const Tree: ForwardRefComponent<TreeProps>;

// @public (undocumented)
export const treeClassNames: SlotClassNames<TreeSlots>;

// @public (undocumented)
export type TreeContextValue = {
    level: number;
    openSubtrees: string[];
    focusFirstSubtreeItem(target: TreeItemElement): void;
    focusSubtreeOwnerItem(target: TreeItemElement): void;
    requestOpenChange(data: TreeOpenChangeData): void;
};

// @public
export const TreeItem: ForwardRefComponent<TreeItemProps>;

// @public (undocumented)
export const treeItemClassNames: SlotClassNames<TreeItemSlots>;

// @public
export const TreeItemLayout: ForwardRefComponent<TreeItemLayoutProps>;

// @public (undocumented)
export const treeItemLayoutClassNames: SlotClassNames<TreeItemLayoutSlots>;

// @public
export type TreeItemLayoutProps = ComponentProps<TreeItemLayoutSlots>;

// @public (undocumented)
export type TreeItemLayoutSlots = {
    root: Slot<'div'>;
};

// @public
export type TreeItemLayoutState = ComponentState<TreeItemLayoutSlots>;

// @public
export type TreeItemProps = ComponentProps<TreeItemSlots>;

// @public (undocumented)
export type TreeItemSlots = {
    root: NonNullable<Slot<ARIAButtonSlotProps<'div' | 'a'>>>;
};

// @public
export type TreeItemState = ComponentState<TreeItemSlots>;

// @public (undocumented)
export type TreeProps = ComponentProps<TreeSlots> & {
    openSubtrees?: string | string[];
    defaultOpenSubtrees?: string | string[];
    onOpenChange?(event: TreeOpenChangeEvent, data: TreeOpenChangeData): void;
};

// @public (undocumented)
export const TreeProvider: Provider<TreeContextValue | undefined> & FC<ProviderProps<TreeContextValue | undefined>>;

// @public (undocumented)
export type TreeSlots = {
    root: Slot<'div'>;
};

// @public
export type TreeState = ComponentState<TreeSlots> & TreeContextValue & {
    open: boolean;
};

// @public
export const useTree_unstable: (props: TreeProps, ref: React_2.Ref<HTMLElement>) => TreeState;

// @public (undocumented)
export const useTreeContext_unstable: <T>(selector: ContextSelector<TreeContextValue, T>) => T;

// @public
export const useTreeItem_unstable: (props: TreeItemProps, ref: React_2.Ref<TreeItemElement>) => TreeItemState;

// @public
export const useTreeItemLayout_unstable: (props: TreeItemLayoutProps, ref: React_2.Ref<HTMLElement>) => TreeItemLayoutState;

// @public
export const useTreeItemLayoutStyles_unstable: (state: TreeItemLayoutState) => TreeItemLayoutState;

// @public
export const useTreeItemStyles_unstable: (state: TreeItemState) => TreeItemState;

// @public (undocumented)
export const useTreeStyles_unstable: (state: TreeState) => TreeState;

// (No @packageDocumentation comment for this package)

```
